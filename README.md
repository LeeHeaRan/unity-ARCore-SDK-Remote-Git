# unity-ARFoundation-Remote-Git   
### AR 개발 환경 설정.   
1. android switch platform   
2. player settings에서 player에서 GraphicsAPIs의 Vulkan제거. Minimum API Level을 android 7.0 'Nougat'로 변경. Configuration에서 Scriping Vackend를 IL2CPP로 변경.   
TargetArchitectures의 ARM64체크.   
3. Package Manager에서 UnityRegistry선택 AR Foundation, ARCore XR Plugin을 install.   
4. player setting에서 XR Plugin Management에서 안드로이드 아이콘 클릭. ARCore 체크.   


### 지금부터 리모트 환경 설정.   
1. https://github.com/google-ar/arcore-unity-sdk/releases 에서 최신 버전 SDK 다운 및 임포트.   
2. Package Manager의 왼쪽 상단 + 클릭. Add Packge From Git URL... 클릭.   
3. com.unity.multiplayer-hlapi와 com.unity.xr.leagcyinputhelpers를 install.   
4. 이미지   
최종적으로 들어가야할 객체들.   
![01](https://user-images.githubusercontent.com/48555909/129133195-fd95abd1-e3e6-49d6-8563-c79363554941.png)   
필요한 것들을 넣어 준다.   
![02](https://user-images.githubusercontent.com/48555909/129133230-e4408f8c-a23b-4482-9ff7-5c79e5680e62.png)   
![03](https://user-images.githubusercontent.com/48555909/129133236-1bb11e88-5f9b-4a97-b78a-ae88a2d7de35.png)   
검색하여 필요한 스크립트와 객체들을 찾아서 넣어준다.   
![04](https://user-images.githubusercontent.com/48555909/129133254-ca711fbf-73ef-4343-89df-96109c08a267.png)   
![05](https://user-images.githubusercontent.com/48555909/129133242-bb48cfd4-4c9d-430d-afc1-aeb101fbb95e.png)   
![06](https://user-images.githubusercontent.com/48555909/129133245-b15ad234-4118-4ce2-97cb-061f4eeed286.png)   
![07](https://user-images.githubusercontent.com/48555909/129133247-b83a4d7a-d01c-47e5-8f1a-4fd6badadf27.png)   
![08](https://user-images.githubusercontent.com/48555909/129133249-85ff2ad9-bfd1-444e-8db3-bfde59ee7139.png)   
![09](https://user-images.githubusercontent.com/48555909/129133252-f8613220-d9e7-477b-933b-4a2e2d140fb9.png)   

5. InstantPreview.apk 폰에 설치하기.   
6. USB 연결해서 빌드 확인.   
 
