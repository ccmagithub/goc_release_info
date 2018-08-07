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
* [PaaS source code](#infra-team-source-code)
* [Service Portal source code](#sp-team-source-code)
* [Infra / SP document](#infra--sp-document)
* [Infra CI Test plan report](#infra-ci-test-plan-report)
* [SP Test plan report](#sp-test-plan-report)
* [TS-UAT Test plan report](#ts-uat-test-plan-report)

### New features
------
* Job API.
* Private registry managment API.
* OpenStack reconfiguration.

[回到目錄 :arrow_heading_up:](#目錄)

### Enhancement/Improvement
------
* API performance enhancement.
* Load balancer enhancement.

[回到目錄 :arrow_heading_up:](#目錄)

### Removed/Retired features
------
* Job type is not supported in Docker solution.
* Harbor user/project is not bound to OpenStack user/tenant.

[回到目錄 :arrow_heading_up:](#目錄)

### Fixed issues
------
* 在 newton 的 openstack 中無法透過 metering 取得 bandwidth 的資料 (GOC-376)
* [2017.3.0] UAT測試, System Admin Guide文件內容與現況不符 (GOC-380)
* 刪除 Site 時，GOC DB 會一直卡在 Deleting，但Site 已被刪除 (GOC-391)

[回到目錄 :arrow_heading_up:](#目錄)

### Known issues
------
* Cloudinit is not working properly result in cutomizing user account fail. (GOC-35)
* Stuck on the notification page while deleting three instances. (GOC-56)
* 進入“通知”的訊息列表頁面，使用者無法切換群組 (GOC-108)

[回到目錄 :arrow_heading_up:](#目錄)

### Infra team source code
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

### SP team source code
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)

### Infra / SP document
------
* smb://172.16.200.50/Gemini_fileserver/Release/2018.1/2018.1.0/Document

[回到目錄 :arrow_heading_up:](#目錄)

### Infra CI Test plan report
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)

### SP Test plan report
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)

### TS-UAT Test plan report
------
TBD

[回到目錄 :arrow_heading_up:](#目錄)
