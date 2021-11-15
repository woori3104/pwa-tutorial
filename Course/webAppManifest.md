
# Web App Manifest란

- Progressive Web App의 설치와 앱 구성정보를 담고 있는 json형식의 설정 파일
  - 앱 아이콘, 화면 런쳐 방식 및 배경색, 시작페이지 등을 설정할 수 있는 JSON파일
- 앱 관련 구성정보에는 아래와 같은 항목들이 설정됩니다. 
  - Start URL : 웹 앱이 시작되는 지점
  - Launch Image : 웹 앱 시작 화면
  - Display Type : 웹 앱의 화면 형태 
  - Display Orientation : 웹 앱 화면 방향 
  - App Icon : 앱 아이콘 이미지와 크기

- Web App Manifest 파일 구조 
```
{
  "short_name": "앱 아이콘 이름",
  "name":"하단 설치 배너에 표기될 이름 & 앱에서 검색시 키워드", 
  "icons": [
    {
      "src" : "dis/images/icons/icon-32x32.png",
      "type" : "image/png",
      "sizes" : "32x32"
    },
    {}
  ],
  "background_color":"#E88E5",
  "display":"standalone",
  "start_url":"./"
}
```