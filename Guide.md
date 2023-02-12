[< 上一頁 Back](https://uwsp.justinl.in/)

# 安裝說明 Installation Guide

## 硬體挑選 Hardware Selection
測試過的硬體可以參考[硬體測試清單](https://github.com/justinlin099/UWSP-Universal-Windows-7-Project/blob/main/Qualified%20Vendors%20List.html)。   
Check tested hardware [here](./Qualified%20Vendors%20List.html).

>我大部分的主機板都是 msi 的，如果現在買不到清單上的硬體的話也盡量挑選 msi 的比較不會有相容性問題。  
>Most of my motherboards are manufacturered by msi. If you can’t buy the hardware on the list now, choose msi to avoid compatibility problems.

### 更換主機板的網路卡 Replace Wi-Fi/BT card on the motherboard

目前沒有任何驅動程式支援 Wi-Fi 6 的網路卡(AX200/AX210)，所以如果需要主機板的無線功能的話就必須更換板子上的網路卡。  
There is currently no driver supporting Wi-Fi 6 network cards (AX200/AX210), so if you need the wireless function on the motherboard, you must replace the Wi-Fi card on the board.

>注意：每張板子的設計可能不一樣，更換時請務必小心。  
>Caution: Step may vary by each Motherboard, always be careful when you modifying any electronic devices.

1. 拆下主機板上的 IO 裝甲。  
   Remove the IO shield on the motherboard.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218054065-cb3e19da-858e-47b8-ae7d-86349bfb515e.png" width="400">
   
2. 拆下網卡背面的螺絲並移除網路卡。  
   Unscrew the Wi-Fi Card and Remove it from the motherboard.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218056023-cd05e17a-f901-4c01-97e6-cac5339bb953.png" width="400">  
   <img src="https://user-images.githubusercontent.com/61717681/218056279-b042e0e3-916b-4258-b58c-191755dc59dd.png" width="400">  
   
3. 拆開屏蔽罩並且更換裡面的網路卡。  
   Open the shell and replace the Wi-Fi card.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218056948-fca9e84d-d812-4f51-9ed0-8ab2a0890b74.png" width="400">  
   
4. 照著原本的步驟把東西裝回去。  
   Follow the original steps to put things back together.  
   
5. 讚讚！你現在有一張完全支援 Windows 7 的主機板了！  
   Ta da! You now have a motherboard that fully supports Windows 7!  
  




## 需要預先下載的東西 Things need to download first
1. 安裝隨身碟製作工具 [Rufus](https://rufus.ie/)。  
   Bootable Media Creation Tool [Rufus](https://rufus.ie/)  
   
2. [UWSP 安裝映像檔](https://drive.google.com/drive/folders/1iYQWDN9JloSDOoZpD-azCkSLe84VzKvz?usp=sharing)。  
   [UWSP installation ISO image](https://drive.google.com/drive/folders/1iYQWDN9JloSDOoZpD-azCkSLe84VzKvz?usp=sharing)  


## 安裝步驟 Installation steps
1. 準備一支要拿來灌系統的 USB 隨身碟（容量 8GB 以上），並且備份所有資料（原本內部的資料會全部清除）。  
   Prepare an USB flash drive(8GB or up) and backup all the files in it(All the data in the flash drive will be wiped).  
   
2. 插入隨身碟並開啟 Rufus。  
   Insert the USB flash drive and open Rufus.  
   
3. 在裝置部分選擇你的隨身碟，開機模式的檔案選擇你下載下來的 UWSP ISO，其他選項保留預設（如圖所示）。  
   Select your USB flash drive in the "Device" option, select UWSP ISO in the "Boot selection" option, other options remain default(as shown in the screenshot).   
   
   <img src="https://user-images.githubusercontent.com/61717681/218296980-d48066de-1103-4b68-8334-7ef6ad015c87.jpg" width="418">  
   
4. 按下執行開始寫入映像。  
   Click START button to start writing the ISO image.  
  
   <img src="https://user-images.githubusercontent.com/61717681/218297124-f328a101-0735-4f49-8aef-2eaa6a82a3ae.jpg" width="418">  
   <img src="https://user-images.githubusercontent.com/61717681/218297143-0f697498-b28e-4e34-90d5-83edd545b5df.jpg" width="418">  
   
5. 插入安裝隨身碟並且開機，在開機時長按 `del` 鍵進入 BIOS。  
   Insert USB flash drive and power on the computer, long press `del` button to enter the BIOS.  
   >注意：安裝時請勿在主機板上的 USB 2.0 插孔插入任何裝置，否則會造成藍屏  
   >Caution: Please don't use any USB 2.0 port while you install the system(keyboard, mouse, USB Flash Drive, etc.), otherwise it might cause BSOD.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218298091-b9e10708-cd06-4c2d-8901-e0915a256e46.jpg" width="960">  
   
6. 在 BIOS 內找到 CSM/UEFI 模式選項，並且選擇開啟 CSM 模式。  
   Find BIOS CSM/UEFI Mode option and select CSM Mode.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218299065-39880ce5-5e4f-47f3-ab63-c3f9a8f50df6.jpg" width="960">  
  
   >不同家主機板廠商的選項名稱可能不同。  
   >The name of the option may vary by each motherboard manufacturer.  
   
7. 按下 `F10` 儲存選項並退出。  
   Press `F10` to save and exit BIOS.  
   
   <img src="https://user-images.githubusercontent.com/61717681/218299260-3d5af3d8-8e9d-4159-8c95-03f8b08a731b.jpg" width="960">  
   
8. 退出後長按開機選單鍵進入開機選單。  
   After exit the setup, long press boot menu hotkey to enter boot menu.
   >開機選單鍵 Boot Menu Hotkey:  
   >msi: `F11`  
   >ASUS: `F8`  
   >GIGABYTE: `F12`  

   <img src="https://user-images.githubusercontent.com/61717681/218303812-aa784f59-b4a4-477b-a6aa-3fb7c332de5b.jpg" width="960">  
   
9. 選取你的隨身碟（名稱通常為 UEFI:"隨身碟的型號"）並按下 `ENTER` 。  
   Select your USB flash drive(Usually displayed as UEFI:"the model of the USB flash drive") and press `ENTER`.  
   
10. 進入安裝畫面後按下 `下一步`。  
    Press `Next` when you entered the Windows Setup screen.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218304612-2505df9b-faf1-4116-ab9b-331be4f337be.jpg" width="960">  
    
11. 按下 `立即安裝`。  
    Press `Install Now`.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218304730-220f6b40-554a-427a-bc40-c9aa47e9af62.jpg" width="960">  
    
12. 按下 `我沒有產品金鑰`。  
    Select `I don't have product key`.  
   
    <img src="https://user-images.githubusercontent.com/61717681/218304893-b01b934e-7bbe-4848-ba26-47735fe58a85.jpg" width="960">  
     
13. 選擇你想安裝的 Windows 7 版本。  
    Select the Windows 7 edition you want to install.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218304972-c13ed817-7026-468c-bae5-c0ebdf5ef866.jpg" width="960">  
    
14. 同意軟體授權條款。  
    Accept to the EULA.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305062-f33dd5bf-0a59-46d4-8a8d-72d9563b8286.jpg" width="960">  
    
15. 選擇自訂安裝。  
    Select custom install.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305139-e11d4892-755b-48d6-b95e-491fcf769d20.jpg" width="960">  
    
16. 選擇你要安裝系統的分區並且按 `下一步`。  
    Select the partition that you want to install the system and press `Next`.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305259-3e5aee94-1eae-4756-899c-5362a7269da0.jpg" width="960">  

17. 請靜待系統安裝完成。（大約需要五分鐘）  
    Please wait the system to install. (About 5 mins.)  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305427-18053c0b-8f4f-4c03-8383-f7180fbf5b37.jpg" width="960">  
    
18. 依據指示設定裝置。  
    Setup the device according to the instructions.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305490-1d61c46a-7e40-4126-a628-4107071cd50b.jpg" width="960">  
    
19. 等待 Windows 完成設定。（大約需要四分鐘）  
    Wait Windows to complete the setup. (About 4 mins.)
    
    <img src="https://user-images.githubusercontent.com/61717681/218305571-10c32090-5145-43ea-ad5b-7ed2caa2f025.jpg" width="960">  

20. 安裝顯示卡驅動及瀏覽器等程式就完成了。  
    Install GPU Driver and browser.  
    
    <img src="https://user-images.githubusercontent.com/61717681/218305809-5dc5e233-1c4a-4b70-acc9-98919f982824.jpg" width="480">
    <img src="https://user-images.githubusercontent.com/61717681/218305813-a7cb2f2e-a992-4c64-b27d-e7bfc4589ccb.jpg" width="480">  
    <img src="https://user-images.githubusercontent.com/61717681/218305828-de2eea67-6a5f-4fba-80aa-9956c3252a01.jpg" width="480">
    <img src="https://user-images.githubusercontent.com/61717681/218305841-e6cbf65e-efef-404c-abb9-8163541e036e.jpg" width="480">  
    <img src="https://user-images.githubusercontent.com/61717681/218305856-b47dd95d-737d-4309-939c-997de0c6aa8f.jpg" width="960">



    


   



