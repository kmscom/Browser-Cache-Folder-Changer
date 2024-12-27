## Web Browser Cache Folder Changer 사용자 가이드

이 프로그램을 사용하려면 ImDisk Toolkit같은 램 디스크 드라이브가 설정되어 있어야 한다. 아직 램 드라이브가 설정되어 있지 않다면 아래 가이드를 참고해서 램 드라이브 프로그램을 설치하고, 램 드라이브를 설정한다.
- [ImDisk Toolkit Install Guide](https://github.com/kmscom/Browser-Cache-Folder-Changer/blob/main/User%20Guide/ImDisk%20Install%20Guide%20-%20KOR.md)

### 설치 프로그램 다운로드

Web Browser Cache Folder Changer 프로그램의 설치 파일은 아래 링크를 클릭해서 다운로드 받는다.
*   [web\_browser\_cache\_folder\_changer\_setup.exe](https://github.com/kmscom/Browser-Cache-Folder-Changer/blob/main/Release/web_browser_cache_folder_changer_setup.exe)

또는 아래 Release 링크에서 최신 버전을 다운로드 받는다.
- [https://github.com/kmscom/Browser-Cache-Folder-Changer/releases](https://github.com/kmscom/Browser-Cache-Folder-Changer/releases)

### 설치
1) **web\_browser\_cache\_folder\_changer\_setup.exe** 프로그램을 실행한다.

2) 다음과 같은 메뉴가 나타날 것이다.
    - 사용자의 상황에 따라 본인만 사용할 것인지, 모든 사용자용으로 설치할지 선택한다.
    ![Select Setup Install Mode](image/1.%20install_1_kr.png)

    여기서는 "모든 사용자용으로 설치"하는 사례를 설명한다.

3) 모든 사용자용으로 설치하는 경우, 다음 윈도우가 나타난다.
    - 모든 사용자용으로 설치하려는 경우에는 "privilege permission"이 필요하다. "예"를 선택하고 설치를 계속한다.
    ![User Account Control](image/1.%20install_2_kr.png)

4) 설치 언어 선택 윈도우가 나타난다. 
    - 한국어나 영어를 선택하고 "확인" 버튼을 누른다.

    ![Select Setup Language](image/1.%20install_3_kr.png)

5) 사용권 계약 윈도우가 나타난다.
    - 이 프로그램은 누구나 자유롭게 사용할 수 있는 무료 프로그램이다. 단, 배포하는 경우 Copyright을 같이 배포해야 한다.
    - "동의합니다(A)"를 선택하고 "다음(N)" 버튼을 누른다.
    ![License Agreement](image/1.%20install_4_kr.png)

6) 프로그램을 설치할 대상 위치 폴더를 선택하고 "다음(N)" 버튼을 누른다.
    - 디폴트 위치를 보통 사용한다.

    ![Select Destination Location](image/1.%20install_5_kr.png)

7) "바탕 화면에 바로가기 만들기(D)" 체크박스 옵션을 선택하고 "다음(N)" 버튼을 누른다.
    ![Select Additional Tasks](image/1.%20install_6_kr.png)

8) 이제 설치 준비가 완료되었다. "설치(I)" 버튼을 누른다.
    ![Ready to Install](image/1.%20install_7_kr.png)

9) 설치 완료 후 마지막으로 다음 윈도우가 나타난다.
    - "마침(F)" 버튼을 눌러 설치를 마무리한다.
    ![Completing the Web Browser Cache Folder Changer Setup Wizard](image/1.%20install_8_kr.png)

    - "Web Browser Cache Folder Changer 실행" 체크박스가 체크되어 있지 않음에 주목하자.
    - 만일 이 체크박스가 체크되어 있으면 다음과 같은 에러 윈도우가 나타날 수 있다. 이 겨우 그냥 무시하면 된다.
    ![Unable to execute file.](image/1.%20install_9_kr.png)

### 프로그램 실행하기
1) 바탕화면에 있는 아래 프로그램 아이콘을 더블클릭 해서 실행한다.

    ![Web Browser Cache Folder Changer](image/2.%20execute.png)

2) 프로그램을 실행하면 다음 윈도우가 나타난다.
    - 이 프로그램은 폴더에 대한 symbolic link를 생성하기 위해 privilege permission이 필요하다.
    - "예" 버튼을 눌러 실행을 계속한다.

    ![User Account Control](image/2.1%20execute_kr.png)

3) 다음과 같은 메인 프로그램 윈도우가 나타난다.

    ![Browser Cache Folder Changer](image/3.%20main_1.png)

### 주요 기능
Browser Cache Folder Changer 프로그램은 웹 브라우져의 캐쉬 폴더를 램 드라이브 상의 새로운 위치로 심볼릭 링크를 생성한다.
웹 브라우져 캐쉬 파일이 램 드라이브에 생성되도록 함으로써 실행 속도를 빠르게 하고, 저장 장치로의 IO를 제거하려는 것이다.

![Browser Cache Folder Changer with Number](image/3.%20main_2.png)

이 프로그램의 일반적인 사용 방법은 다음과 같다.

#### 1️⃣ 웹 브라우져를 선택한다.
- 여기에서는 "Microsoft Edge"를 선택했다.
- 다음 윈도우가 나타난다.

    ![Select User Profile](image/3.%20main_3_kr.png)

    웹 브라우져의 캐쉬 폴더는 사용하는 프로파일의 이름에 따라 다를 수 있다.
        - 만약 어떤 프로파일을 사용하고 있는지 모르겠다면 "Default"를 선택한다.
        - 프로파일 이름이 "Profile 1" 또는 "Profile 2"인 경우 선택하고 "Ok" 버튼을 누른다.
        - 다른 프로파일 이름을 사용하고 있다면 "Custom:" 옆에 있는 필드에 입력하고 "Ok" 버튼을 누른다.

#### 2️⃣ 웹 브라우져의 현재 캐쉬 폴더를 선택한다.
- 기본 캐쉬 폴더 경로가 입력창에 이미 등록되어 있을 것이다.
- 만약 이 경로가 올바르지 않다면 "Select the Browser's Default Cache Fiolder" 버튼을 눌러서 기본 캐쉬 폴더를 선택한다.
    - "Open Folder" 버튼을 눌러서 해당 폴더가 잘 선택되었는지 확인할 수 있다.
    - 웹 브라우져를 실행하며 이 폴더에 캐쉬 파일이 생성되고 있는지 확인해 보자.
- ![Select the Default Cache Folder](image/3.%20main_4.png)

- "Microsoft Edge" 웹 브라우져를 실행한 적이 없다면 기본 캐쉬 폴더가 존재하지 않을 수도 있다.

#### 3️⃣ 웹 캐쉬 파일을 저장할 램 드라이브의 폴더 위치를 지정한다.
- 아직 램 드라이브가 설정되어 있지 않다면, 램 드라이브를 우선 설정한다.
- 여기서는 "R:\webCacheTop\" 폴더 아래에 웹 브라우져의 모든 캐쉬 파일들을 웹 브라우져들 별로 저장하려고 한다.
    - "R:\webCacheTop\" 폴더가 생성되어 있지 않다면 미리 생성한다.
- "Select a RAM Drive Folder (ex: R:\webCacheTop)" 버튼을 눌러 "R:\webCacheTop\" 폴더를 선택한다.
- ![Select the Web Cache Top Folder](image/3.%20main_5.png)

- 이제 "Browser's New Cache Folder"가 다음과 같이 지정될 것이다.
    - "R:\webCacheTop\edgeCache"로 설정되었다.
    ![New Cache Folder](image/3.%20main_6_kr.png)

#### 4️⃣ 캐쉬 폴더 경로 재설정 하기
- 이제 "Redirect Cache Folder" 버튼을 눌러 웹 브라우져의 캐쉬 폴더를 새로운 경로로 설정한다.

C:\Users\CacheFolderChangerKr\AppData\Local\Microsoft\Edge\User Data\Default\Cache\Cache_Data
-->
R:\webCacheTop\edgeCache

- "Redirect Cache Folder" 버튼을 누를 때 다음과 같은 에러 윈도우가 나타날 수 있다.
    ![Process Check Error](image/3.%20main_7.png)

- 이것은 Microsoft Edge 브라우져가 실행중일 때 나타난다. Microsoft Edge 브라우져를 종료하고 진행해야 한다.
- 주의: 여기에서 "Yes" 버튼을 누르면 실행중인 Microsoft Edge 브라우져를 종료시킨다.
    ![Process terminate](image/3.%20main_7_1.png)

- 웹 브라우져 캐쉬 폴더 재설정에 성공하면 다음과 같은 윈도우가 나타난다. "확인" 버튼을 눌러 계속한다.
![Redirect Cache Folder Success](image/3.%20main_8_kr.png)

#### 캐쉬 폴더 재설정이 잘 되었는지 확인하기 
- 웹 브라우져의 캐쉬 폴더 재설정이 잘 되었는지 확인해 보자.
- Microsoft Edge 브라우져를 실행하고, 새로운 캐쉬 폴더를 탐색기로 방문해 보자.
    - "Browser's New Cache Folder" 버튼과 같은 행에 있는 "Open Folder" 버튼을 누른다.
- 다음과 같이 새로운 캐쉬 폴더 위치에 캐쉬 파일들이 생성되고 있는지 확인한다.
    - ![Cache files](image/3.%20main_9.png)

#### 5️⃣ 캐쉬 폴더 경로 원복하기
- 만약 웹 브라우져의 캐쉬 폴더 변경을 원래대로 복원하고 싶다면, "Restore Cache Folder" 버튼을 누른다.
   - 웹 브라우져를 우선 선택하고, "Restore Cache Folder" 버튼을 누른다.

### 6️⃣ 램 드라이브 프로그램들
- 무료로 사용할 수 있는 램 드라이브 프로그램을 다운로드 받을 수 있는 곳이다.
    - [ImDisk](https://sourceforge.net/projects/imdisk-toolkit/)
    - [AMD Radeon(TM) RAMDisk](https://www.radeonramdisk.com/software_downloads.php)

### 7️⃣ 이 프로그램의 개발자 후원 방법
- 이 프로그램이 마음에 든다면 아래 링크를 방문해 주세요.
    - [Go for DRAM shopping!!!](https://semiconductor.samsung.com/dram/ddr/ddr5/?cid=us_pd_ppc_google_b2b_none_sem-b2b_text_b2b_samsung%20ddr5&utm_source=google&utm_medium=pd_ppc&utm_campaign=us_b2b_none_sem-b2b&utm_content=text_b2b&utm_term=samsung%20ddr5&gad_source=1)
    - [GitHub (Browser Cache Folder Changer)](https://github.com/kmscom/Browser-Cache-Folder-Changer)
    - [Support Developer if you like this application ($1)](https://www.paypal.com/paypalme/CacheFolderChanger?country.x=US&locale.x=en_US)

### 8️⃣ 프로그램 종료
- "Quit" 버튼을 눌러 프로그램을 종료한다.

### 9️⃣ 사용자 가이드
- 사용자 가이드를 웹 브라우져에 오픈한다.

### 🔟 로그 열기
- 웹 브라우져의 캐쉬 폴더 설정 작업을 로그 파일에 기록하고 있다. 이 로그 파일을 오픈한다.

### 11 "Open Folder" 버튼들
- 해당 폴더를 탐색기로 오픈한다.
