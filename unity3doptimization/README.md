
# intro

- unity3d 최적화에 대해 경험해 본 것들 위주로 적어본다. 

# usage

- player settings옵션을 꼼꼼하게 확인해 본다.
  - release빌드할때 script optimization등등을 신경쓴다.
- Resources 폴더의 내용은 runtime memory를 잡아 먹는다.
- Assets폴더에 존재하는 모든 script들은 build package에
  포함된다. 사용하지 않는 script들은 삭제하자.
  - [참고](https://unity3d.com/kr/learn/tutorials/temas/best-practices/resources-folder)
- json을 처리할때 minijson보다 JsonUtility를 사용하자. runtime memory를 절약할 수 있다.
