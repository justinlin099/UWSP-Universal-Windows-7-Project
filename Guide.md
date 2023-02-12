[< 上一頁 Back](https://uwsp.justinl.in/)

# 安裝說明 Installation Guide

## 硬體挑選 Hardware Selection
測試過的硬體可以參考[硬體測試清單](https://github.com/justinlin099/UWSP-Universal-Windows-7-Project/blob/main/Qualified%20Vendors%20List.html)   
Check tested hardware [here](./Qualified%20Vendors%20List.html).

>我大部分的主機板都是 msi 的，如果現在買不到清單上的硬體的話也盡量挑選 msi 的比較不會有相容性問題。  
>Most of my motherboards are manufacturered by msi. If you can’t buy the hardware on the list now, choose msi to avoid compatibility problems.

### 更換主機板的網路卡 Replace Wi-Fi/BT card on the motherboard

目前沒有任何驅動程式支援 Wi-Fi 6 的網路卡(AX200/AX210)，所以如果需要主機板的無線功能的話就必須更換板子上的網路卡。  
There is currently no driver supporting Wi-Fi 6 network cards (AX200/AX210), so if you need the wireless function on the motherboard, you must replace the Wi-Fi card on the board.

>注意：每張板子的設計可能不一樣，更換時請務必小心  
>Caution: Step may vary by each Motherboard, always be careful when you modifying any electronic devices.

1. 拆下主機板上的 IO 裝甲
   >Remove the IO shield on the motherboard.  
   ><img src="https://user-images.githubusercontent.com/61717681/218054065-cb3e19da-858e-47b8-ae7d-86349bfb515e.png" width="400">
2. 拆下網卡背面的螺絲並移除網路卡
   >Unscrew the Wi-Fi Card and Remove it from the motherboard.  
   ><img src="https://user-images.githubusercontent.com/61717681/218056023-cd05e17a-f901-4c01-97e6-cac5339bb953.png" width="400">  
   ><img src="https://user-images.githubusercontent.com/61717681/218056279-b042e0e3-916b-4258-b58c-191755dc59dd.png" width="400">
3. 拆開屏蔽罩並且更換裡面的網路卡
   >Open the shell and replace the Wi-Fi card.  
   ><img src="https://user-images.githubusercontent.com/61717681/218056948-fca9e84d-d812-4f51-9ed0-8ab2a0890b74.png" width="400">
4. 照著原本的步驟把東西裝回去 
   >Follow the original steps to put things back together.
5. 讚讚！你現在有一張完全支援 Windows 7 的主機板了！
   >Ta da! You now have a motherboard that fully supports Windows 7!
  




## 需要預先下載的東西 Things need to download first
1. 安裝隨身碟製作工具 [Rufus](https://rufus.ie/)  
   >Bootable Media Creation Tool [Rufus](https://rufus.ie/)
2. [UWSP 安裝映像檔](https://drive.google.com/drive/folders/1iYQWDN9JloSDOoZpD-azCkSLe84VzKvz?usp=sharing)  
   >[UWSP installation ISO image](https://drive.google.com/drive/folders/1iYQWDN9JloSDOoZpD-azCkSLe84VzKvz?usp=sharing)


## 安裝步驟 Installation step
1. 準備一支要拿來灌系統的 USB 隨身碟（容量 8GB 以上），並且備份所有資料（原本內部的資料會全部清除）  
   >Prepare an USB flash drive(8GB or up) and backup all the files in it(All the data in the flash drive will be wiped).  
2. 插入隨身碟並開啟Rufus  
   >Insert the USB flash drive and open Rufus.  
3. 在裝置部分選擇你的隨身碟，開機模式的檔案選擇你下載下來的 UWSP ISO，其他選項保留預設（如圖所示）  
   >Select your USB flash drive in the "Device" option, select UWSP ISO in the "Boot selection" option, other options remain default(as shown in the screenshot).  
   ><img src="https://user-images.githubusercontent.com/61717681/218296980-d48066de-1103-4b68-8334-7ef6ad015c87.jpg" width="418">

