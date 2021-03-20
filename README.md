# Consent_Signing_System
專案-QCC品質指標競賽 - 數位化同意書簽署系統

---檔案中，部分內容涉及企業資訊安全，因而刪除或使用隱碼方式呈現，敬請見諒。---

---所有專案所使用到的圖片皆為公司美編人員協助出圖。---

一、專案目的:由資訊室、病歷室、護理部與門住組組成的合作團隊，運用QCC手法發現醫院同意書種類繁多、流程複雜，希望開發數位化同意書簽署系統，進而達到減少紙張浪費、提升簽署正確率、改善人工作業流程。

二、功能概述:

1.於同意書數位化簽署APP介面輸入病人身分證字號，系統自動帶出該民眾應簽署之電子同意書供病人瀏覽。

2.病人輸入須填欄位並進行簽署完成後，公司員工(護理師、行政人員等)判斷簽屬完整性並確認上傳後，系統合併電子同意書與病人簽名圖檔，將合併簽署完畢的檔案上傳至伺服器。

3.公司員工使用後台管理系統，維護同意書版本並調閱、補上傳、列印同意書。

三、所負責的項目與使用的技術:

1.同意書電子檔Web Service : 使用ASP.NET Web Service、Microsoft.ReportViewer.WebForms元件開發產生同意書電子檔以及上傳簽署檔案之服務。

2.同意書數位化簽署APP : 使用Xamarin.Forms 開發簽暑APP。

3.管理後台 : 使用ASP.NET WinForm開發管理者後台進行同意書資料管理、調閱、補上傳、列印。

四、專案成果:

1.於競賽中獲得佳作。

2.後續應用資訊室，目前[資訊安全切結書]已上線。
