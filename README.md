# backend

npm start를 하면 수행됩니다. 
http://localhost:3000/ 에서 결과를 확인할 수 있습니다. 

bin: 실행 파일을 관습적으로 /bin 에 넣어둔다고 합니다. npm start를 하면 bin 내의  www.js를 통해 서버가 구동됩니다. 
modules: 모듈 파일이 들어갑니다.
모듈은 특정한 기능을 하는 함수나 변수들의 집합인데 코드 짤때 파일 분리해서 짜는거를 말하는 것 같습니다. 
public: 외부에서 접근 가능한 파일입니다. 
routes: 라우터가 들어갑니다. 대부분 여기에 코드를 짜면 될 것 같습니다. 
라우터는 method랑 URL이 있는 것들 (router.get('/', ... ))을 의미합니다. get은 get요청이 오면 어떤 작업을 해줄것인지 입니다! 
view: 템플릿 파일이 들어갑니다. 

app.js : 익스프레스 서버 코드가 담긴 파일입니다. 서버 구동의 핵심이 되는 파일입니다. 
package-lock.json: 패키지간 의존관계를 명확하게 표시하는 파일이라고 하는데 저희가 작성하는 파일은 아닌 듯 합니다. 
package.json: 프로젝트에 대한 정보와 사용 중인 패키지에 대한 정보를 담은 파일입니다. 


처음 파일을 받으시고 npm install을 터미널에 입력하시면 패키지가 node_modules 폴더가 만들어지고 패키지가 설치될거예요! 
