#ubuntu命令

  查看所有已安装软件包的列表：apt-mark showmanual
                            dpkg --get-selections
                            
                            
  查看网络：netsta -an |grep 8080           



  windows子系统导入导出
        参考文章：https://www.windows10.pro/wsl-export-import-linux-subsystem/
        
        查看子系统:  wsl.exe --list --running
        导出子系统： wsl --export Ubuntu E:\WSL\Ubuntu.tar
        导入子系统： wsl.exe --import Ubuntu_20190315 E:\WSL\Ubuntu_20190315 E:\WSL\Ubuntu.tar
        立即运行该Linux子系统: wsl --distribution Ubuntu_20190315
