# Release information for GOC product.
* Version
  * 2018.1.1
* Fileserver read-only account
  * geminiuser/iltwagemini
  
****

## 目錄
* [New features](#new-features)
* [Enhancement/Improvement](#enhancementimprovement)
* [Removed/Retired features](#removedretired-features)
* [Fixed issues](#fixed-issues)
* [Known issues](#known-issues)
* [Release Package](#release-package)
* [Document](#document)
* [Test plan report](#test-plan-report)
* [TS-UAT Test plan report](#ts-uat-test-plan-report)

## _New features_
------
* ~~Job API.~~
* ~~Private registry managment API.~~
* ~~OpenStack reconfiguration.~~

[回到目錄 :arrow_heading_up:](#目錄)

## _Enhancement/Improvement_
------
* API performance enhancement.
* Load balancer enhancement.

[回到目錄 :arrow_heading_up:](#目錄)

## _Removed/Retired features_
------
* Job type is not supported in Docker solution.
* Harbor user/project is not bound to OpenStack user/tenant.

[回到目錄 :arrow_heading_up:](#目錄)

## _Fixed issues_
------
* 在 newton 的 openstack 中無法透過 metering 取得 bandwidth 的資料 (GOC-376)
* [2017.3.0] UAT測試, System Admin Guide文件內容與現況不符 (GOC-380)
* 刪除 Site 時，GOC DB 會一直卡在 Deleting，但Site 已被刪除 (GOC-391)

[回到目錄 :arrow_heading_up:](#目錄)

## _Known issues_
------
* Cloudinit is not working properly result in cutomizing user account fail. (GOC-35)
* Stuck on the notification page while deleting three instances. (GOC-56)
* 進入“通知”的訊息列表頁面，使用者無法切換群組 (GOC-108)

[回到目錄 :arrow_heading_up:](#目錄)

## _Release Package_
------
* Portal Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/Gemini_Portal-2018.1.0.img
* Harbor Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/Gemini_Docker_Registry-2018.1.0.img
* Log Server Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/Gemini_LogMgt_Server-2018.1.0.img
* System Monitor
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/System Monitor

[回到目錄 :arrow_heading_up:](#目錄)

## _Document_
------
* smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/Document

[回到目錄 :arrow_heading_up:](#目錄)

## _Test plan report_
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)

## _TS-UAT Test plan report_
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)
