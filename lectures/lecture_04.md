# MVC패턴 

#### MODEL
데이터를 관리하는 역할  
데이터 베이스에 있는 데이터를 가져와서 다른 객체에 전달하는 역할  
외부 객체로 부터 입력데이터를 받아 데이터 베이스에 넣는 역할  
웹프론트엔드에서는 데이터 베이스에 직접 접근하지 않고 API를 통해 데이터를   
가져오고 그 데이터를 다른 객체에게 전달하는 역할  
외부 객체로부터 데이터를 입력 받으면 그 데이터를 백엔드 API를 이용해 호출하는 역할  

#### VIEW
MODEL의 데이터를 화면에 그리는 역할  
html,css,js로 구현되어 있음  
사용자가 입력한 데이터를 처리하는 역할  
(사용자가 입력하면 입력 이벤트를 VIEW가 받아 다른 객체에 전달)  

#### CONTROLLER
MODEL과 VIEW는 화면에 직접적으로 연결되어 있지 않다  
MODEL로 부터 데이터를 가져오고 VIEW에게 데이터를 전달  
반대로 VIEW로부터 사용자에게 입력 받은 데이터를 MODEL에 전달  



