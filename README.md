<div align=center>
	<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=SookD%20Github!&fontSize=90" />	
</div>

<div>
	<h2>프로젝트 소개</h2>
	<h4>We decided to make violence detection program by using other open-source for Sookmyung Women's University, OSS Team project.</h4>
	<h4>AI기반 비정상 행동 감지 지능형 CCTV 모델</h4>
	<h4>: 폭력 행위 이미지가 학습된 DNN 모델과 YOLOv5 모델 활용하여 CCTV에서 실시간으로 위험 행동을 감지하는 시스템</h4>
	<h4>팀원 : <a href="https://github.com/lyeonj/">이연재</a>, <a href="https://github.com/angkmfirefoxygal/">김문원</a>, <a href="https://github.com/parkincow/">박은소</a>, <a href="https://github.com/Yeonnies/">김나연</a>
	</h4>
</div>

<div>
	<h2>개발 과정</h2>
	<h4>사용 데이터 : AI hub 의 이상행동 cctv 데이터</h4>
 	<p align = center>
	<img src ="https://github.com/Sook-D/demo-repository/assets/100902438/cd79ec8f-1846-46df-9c69-81e42f791a0e" >
	</p>	
</div>

<div>
	<h2>폭력 감지 시스템 작동 방식 </h2>
	<h4>YOLOv5를 기반으로 하여 제작 </h4>
	<h4>[system diagram]</h4>
	<p align = center>
		<img src="https://github.com/Sook-D/team-repository/assets/100902438/71b4d2e5-95a0-4240-bef8-d9f95a001c68">	
	</p>
	<h4>[system structure]</h4>
	<p align = center>
		<img src="https://github.com/Sook-D/team-repository/blob/main/image/system%20architecture.png">
	<h5>영상 녹화 장치로부터 소스·데이터를 서버로 보낸 후 서버에서 YOLOv5 모델을 통해 폭력 객체 검출 후 클라이언트에 경계상자생성 사진, 객체 감지로그, 폭력 감지 장면 캡쳐 이미지를 전송한다.</h5>
</div>

<div>
	<h2>최종 결과물</h2>
	<h4>[기본 메인페이지 UI]</h4>
	<p align = center>
		<img src="https://github.com/Sook-D/team-repository/blob/main/image/mainpage_default.png">
	</p>
	<h4>[영상 내 폭력이 감지되었을 경우의 메인페이지 UI]</h4>
	<h5> 다음 이미지는 유튜브의 복싱영상을 카메라에 보여주고 폭력 행위를 실시간으로 감지하는 모습을 캡처한 이미지이다.</h5>
	<p align = center>
		<img src="https://github.com/Sook-D/team-repository/blob/main/image/mainpage_detection%20of%20violence.png">
	</p>
	<h4>[폭력 행위 감지 시 캡처된 이미지 리스트]</h4>
	<h5> View Captured Images 버튼을 클릭하면 지금까지 감지된 폭력 행위들이 담긴 이미지 내역이 보여진다.</h5>
	<p align = center>
		<img src ="https://github.com/Sook-D/demo-repository/assets/100902438/ae59a39d-6ea0-4be5-8edc-7cc0be019e65">
	</p>
</div>
