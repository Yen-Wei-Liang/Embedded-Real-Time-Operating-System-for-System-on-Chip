# Embedded-Real-Time-Operating-System-for-System-on-Chip

## 安裝 ROS Noetic在Raspberry Pi 上

### 一、安裝 Raspberry Pi OS

#### (一) 安裝 Rpi-imager (圖形化界面)
```bash=
sudo apt install rpi-imager
rpi-imager
```
#### (二) CHOOSE OS 
![01](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/516848cd-e097-4bb7-99e7-6e35c57dec42)

#### (三) Raspberry Pi OS (other)
![02](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/19f68cfa-22fb-42d9-9e58-faf1fe71386b)

#### (四) Raspberry Pi OS (Legacy)
![03](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/172f4a3a-69c1-4a26-8760-b801c1766ca4)

#### (五) CHOOSE STORAGE 
![01](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/516848cd-e097-4bb7-99e7-6e35c57dec42)

![04](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/c579a996-6c9d-4778-bae0-b00393bf9b14)

#### (六) WRITE 
![01](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/516848cd-e097-4bb7-99e7-6e35c57dec42)

![05](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/d53d1493-ab41-4520-9428-0b59bdc72c24)


### 二、安裝 ROS Noetic

#### (一) 安裝 git

```bash=
sudo apt install git
```
#### (二) 下載 bash 檔案

```bash=
git clone https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip.git
```

#### (三) 執行 bash (一鍵安裝) 
```bash=
cd Embedded-Real-Time-Operating-System-for-System-on-Chip
sudo bash Raspberry_ROS_Noetic_install.sh
```
![06](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/f965b98d-2dfa-41ae-b385-57b02a1a6259)

#### (四) 選擇ROS環境並執行roscore驗證是否安裝成功

```bash=
source /opt/ros/noetic/setup.bash
rescore
```
![07](https://github.com/Yen-Wei-Liang/Embedded-Real-Time-Operating-System-for-System-on-Chip/assets/127264553/0f8e5889-c70a-425c-ad90-05b3e2a51703)
