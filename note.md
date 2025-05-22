# `images/` 資料夾建議結構

| 檔名                     | 用途             | 備註                                         |
|--------------------------|------------------|----------------------------------------------|
| `logo-horizontal.png`    | 橫式標誌         | 48 px 高即可；深綠色底線條版                |
| `logo-square.png`        | 方形標誌         | 社群圖示或手機捷徑                           |
| `hero.jpg`               | 首頁大圖         | 建議 1920×1080 以上、風景或測量現場         |
| `service-uas.jpg`        | UAS 服務主圖     | 建議空拍作業畫面                             |
| `service-lidar.jpg`      | LiDAR 服務主圖   | 直升機／無人機搭載光達                      |
| `service-gps.jpg`        | GPS 監測主圖     | GNSS 基站或天線實景                         |
| `service-sar.jpg`        | SAR 主圖         | 衛星示意或干涉變形圖                         |
| `service-3d-platform.jpg`| 3D 平台主圖      | 網頁 3D 瀏覽截圖                             |
| `service-consult.jpg`    | 顧問主圖         | 業務洽談或研討會場景                         |
| `example-*.jpg`          | 各頁案例示意     | `example-uas-1.jpg` … 依照頁面命名           |

> 📌 **注意事項：**  
> 以上檔名已在程式碼裡佔位，放進 `images/` 後即可正常顯示，解析度控制在約 150 KB 內可兼顧載入速度。


```Plaintext
remote-sensing-site/          # <— 版本庫根目錄
├── index.html                # 首頁
├── uas.html                  # UAS 無人載具
├── lidar.html                # 空載光達掃描
├── gps.html                  # GPS 自動化監測
├── sar.html                  # SAR / DInSAR
├── 3d-platform.html          # 3D 模型展示
├── consult.html              # 技術顧問
├── style.css                 # 全站共用樣式
├── images/                   # 圖片資源
│   ├── logo-horizontal.png
│   ├── logo-square.png
│   ├── hero.jpg
│   ├── service-uas.jpg
│   ├── service-lidar.jpg
│   ├── service-gps.jpg
│   ├── service-sar.jpg
│   ├── service-3d-platform.jpg
│   ├── service-consult.jpg
│   ├── example-uas-1.jpg
│   ├── example-uas-2.jpg
│   ├── example-uas-3.jpg
│   ├── example-lidar-1.jpg
│   ├── example-lidar-2.jpg
│   ├── example-lidar-3.jpg
│   ├── example-gps-1.jpg
│   ├── example-gps-2.jpg
│   ├── example-gps-3.jpg
│   ├── example-sar-1.jpg
│   ├── example-sar-2.jpg
│   ├── example-sar-3.jpg
│   ├── example-3d-1.jpg
│   ├── example-3d-2.jpg
│   ├── example-3d-3.jpg
│   ├── example-consult-1.jpg
│   ├── example-consult-2.jpg
│   └── example-consult-3.jpg
├── README.md                 # （可選）部署說明、專案緣起
├── .gitignore                # （可選）忽略如 .DS_Store 等
└── CNAME                     # （可選）若綁定自訂網域則放此檔
```