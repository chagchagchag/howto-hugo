### windows 에서 go, hugo 설치, hugo 환경 설정 (겁나빠름)

### 참고자료

- [Windows 환경에서 Hugo 설치하기](https://010000.github.io/post/20191214_install_hugo_windows/)
- [github.com/gohugoio/releases](https://github.com/gohugoio/hugo/releases)



### go 설치

[go.dev/dl](https://go.dev/dl/) 에서 원하는 버전의 go 설치파일을 다운로드해서 설치한다.

<br>



#### 설치 확인

```bash
$ go version
```

<br>



### hugo 설치

- [githib.com/gohugoio/releases](https://github.com/gohugoio/hugo/releases) 에서 윈도우 버전을 다운로드해서 압축울 푼다.
- C:\\env\\hugo\\bin  디렉터리를 만들고 압축을 푼 hugo zip 파일 내부의 모든 내용들을 C:\\env\\hugo\\bin 으로 옮겨준다.
- 윈도우 환경변수에 C:\\env\\hugo\\bin 을 등록한다.



#### 설치 확인

```bash
$ hugo version
hugo v0.117.0-b2f0696cad918fb61420a6aff173eb36662b406e+extended windows/amd64 BuildDate=2023-08-07T12:49:48Z VendorInfo=gohugoio
```

<br>

> 만약 windows 버전의 hugo 다운로드 링크가 안보인다면 `Show mor 23 items` 같은 링크를 클릭해서 윈도우버전이 있는지 찾아보면 된다.

<br>



