# drsite vmware

vmware 인프라 환경에서 powercli 를 이용하여 자동화 스크립트를 작성하였습니다.

# 리눅스 서버 powercli 설치

##### 리눅스서버에서 vmware powercli 사용하기 

## 1.1 powershell 설치

### 1.1.1 redhat계열 다운로드 및 설치
https://github.com/PowerShell/PowerShell/releases/download/v7.4.6/powershell-7.4.6-1.cm.x86_64.rpm

sudo dnf install https://github.com/PowerShell/PowerShell/releases/download/v7.4.6/powershell-7.4.6-1.rh.x86_64.rpm


## 1.2 vmware powercli-module 다운로드 및 설치

cd powercli-module
unzip VMware-PowerCLI-13.3.0-24145081.zip

mkdir -p /usr/local/share/powershell/Modules/

cp -rp VMware.* /usr/local/share/powershell/Modules
