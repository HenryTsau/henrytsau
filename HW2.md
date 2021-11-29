# Git
    1.免費、開源專案管理工具
    2.記錄版本更動情形
    3.分散式系統
    4.可離線工作
    5.多人合作專案時
# Linux
    1.作業系統之一
    2.提供所有最基本的功能，像是鍵盤輸入、螢幕輸出，記憶體管理
    3.相對比較不耗資源的系統，常用來處理巨量資料
    4.雲端部署時常使用
# Linux各個目錄存放的內容
    ●/：根目錄，所有檔案皆從根目錄開始，只有root使用者具該目錄的許可權
    ●/root：該目錄為系統管理員，也稱作超級許可權者的使用者主目錄 
    ●/bin：存放著經常使用的命令●/boot：系統啟動時必須讀取的檔案, 包括系統核心
    ●/home：存放普通使用者的家目錄，每個使用者都有自己的家目錄
    ●/etc：放置與系統設定、管理相關的檔案
    ●/usr：這是一個非常重要的目錄，使用者的應用程式和檔案都放在這個目錄下，類似與windows下的program files目錄
    ●/media：可用來做為光碟、軟碟片、隨身碟與其他分割區的自動掛載點
    ●/tmp：供全部使用者暫時放置檔案的目錄
    ●/var：系統執行時, 內容經常變動的資料或暫存檔(log file),都會放置在這個目錄裡
# Linux指令
    cd:變換目錄
    pwd:顯示目前的目錄的所在位置
    ls:顯示目錄下的所有檔案
    touch:建立檔案
    cp:複製
    cat:查看檔案內容
    vi:編輯檔案
    mkdir:建立一個新目錄
    mkdir -p:同時建立多個目錄
    rmdir:刪除一個裡面是空的空目錄
    rm:刪除檔案
    rm -r:強制刪除
    mv:移動，重新命名
# Linux指令-壓縮檔案
## ●gzip
    ○壓縮：gzip FileName
    ○解壓縮：■gunzip FileName.gz■gzip -d FileName.gz8
 ## ●xz
    ○壓縮：xz -z FileName
    ○解壓縮：xz -d FileName.xz
 ## ●tar.gz
    ○壓縮：tar -zcvf FileName.tar.gz DirName
    ○解壓縮：tar -zxvf FileName.tar.gz9
# Linux指令-網路相關
## ●route
    add:新增一條路由規則
    del:刪除一條路由規則
    -net:目的地址是一個網路
    -host:目的地址是一個主機
    target:目的網路或主機
    netmask:目的地址的網路掩碼
    gw:路由資料包通過的閘道器
    dev:為路由指定的網路介面
## ●ping
    ●-n：參數指定封包數
    ●-t：持續監看網路是否正常 
    ●-4 /-6：IPv4/IPv6
    ●-c：指定Ping次數
    ●-s：指定發送的數據字結數
    ●-i：指定收發資訊間隔時間
## ●netstat
    ●查看端口是否被占用：netstat -al grep 3306
    ●查看數據包統計信息：netstat -s
    ●查看路由信息：netstat -r

    
    
    
    
    
    

