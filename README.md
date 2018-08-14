# Release Information for GOC Product.
1. 版本：**2018.1.1**
2. GOC product 主要包含兩個部分： **GOC PaaS** 以及 **Service Portal** 。
3. 本文件部分資訊（如：_New Features_、_Enhancement/Improvement_、_Removed/Retired Features_、_Fixed Issues_、_Known Issues_...）由於內容繁雜，僅列出Top 3的項目，詳細內容請查詢 _Documents_ 內容。
4. 本文件採用 Git 統一管理，利用不同 branch 維護不同版本的資訊。如需觀看不同版本，請切換至相對應的 branch。

****

## 目錄
* [New Features](#new-features)
* [Enhancement/Improvement](#enhancementimprovement)
* [Removed/Retired Features](#removedretired-features)
* [Fixed Issues](#fixed-issues)
* [Known Issues](#known-issues)
* [Release Package](#release-package)
* [Documents](#documents)
* [CI Test Plan Report](#ci-test-plan-report)
* [TS-UAT Test Plan Report](#ts-uat-test-plan-report)

------
## _New Features_
### GOC PaaS
None
### Service Portal
1. Share Zone - Dashboard Job

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Enhancement/Improvement_
### GOC PaaS
1. Job API Enhancement:rescale-like API
2. Flavor API Enhancement
    a. support k8s, job flavor
### Service Portal
1. TBD

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Removed/Retired Features_
### GOC PaaS
None
### Service Portal
1. TBD

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Fixed Issues_
### GOC PaaS
1. 2018.1.0 installer 無法正確安裝 zabbix (GOC-455)
2. [2018.1.0] UAT測試, Fuel installer image裡面提供的hccomputesetting.sh,
hccomputesettingmerger.sh裡面, IF判斷式語法有錯,無法執行 (GOC-456)
3. [2018.1.0] UAT測試, Slurm安裝,沒有說明node所需必要條件(ex: NIC) (GOC-458)
4. 如果有Pod 未開出Container 便進入 Pending 會使celery-worker 的 check_k8s_task 出現問題
5. 成大環境 Pending Job 的 Pod 沒有資料 (GOC-472)
### Service Portal
1. Fixed the Register Request page in User Management that admin can able to see the request and Approve/Reject users.

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Known Issues_
### GOC PaaS
1. ~~Cloudinit is not working properly result in cutomizing user account fail. (GOC-35)~~
2. ~~Stuck on the notification page while deleting three instances. (GOC-56)~~
### Service Portal
1. TBD

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Release Package_
### GOC PaaS
* Portal Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.1/Gemini_Portal-2018.1.1.img
* Harbor Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.1/Gemini_Docker_Registry-2018.1.1.img
* Log Server Image
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.1/Gemini_LogMgt_Server-2018.1.1.img
* System Monitor
  * smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.1/System_Monitor
### Service Portal
* Service Portal Image
  * smb://172.16.200.50/Gemini_fileserver/Release/ServicePortal/3.1/Service_Portal-3.1
* Service Portal GSP
  * smb://172.16.200.50/Gemini_fileserver/Release/ServicePortal/3.1/GeminiServicePortal-3.1.0.gsp
* IaaS GSP
  * smb://172.16.200.50/Gemini_fileserver/Release/ServicePortal/3.1/GSP/IaaS-3.0.0.gsp

[回到目錄 :arrow_heading_up:](#目錄)

------
## _Documents_
### GOC PaaS
* smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.1/Document
### Service Portal
* Service_Portal_gsp_使用說明
  * smb://172.16.200.50/Gemini_fileserver/Release/ServicePortal/3.1/Service_Portal_gsp_使用說明.txt
* 3.1_image_release_note
  * smb://172.16.200.50/Gemini_fileserver/Release/ServicePortal/3.1/3.1_image_release_note.txt

[回到目錄 :arrow_heading_up:](#目錄)

------
## _CI Test Plan Report_
### GOC PaaS
* TBD
### Service Portal
* TBD

[回到目錄 :arrow_heading_up:](#目錄)

------
## _TS-UAT Test Plan Report_
### GOC PaaS
* TBD
### Service Portal
* TBD

[回到目錄 :arrow_heading_up:](#目錄)
