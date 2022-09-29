# codesimility
파이썬 코드간의 유사성 판단

코드 유사성 판단은 메타코드에서 진행한 딥러닝 프로젝트에 참여하 내용입니다.

김두영 멘토의 진행으로 데이콘 코드 유사성 AI 대회의 자료를 사용하였습니다. https://dacon.io/competitions/official/235900/overview/description

진행한 모델은 RNN을 사용하여 두 코드의 유사성을 판단하는 프로그램입니다.

csRNNwDict는 bert와 같이 미리 학습된 토크나이저를 사용하지 않고, 파이썬 코드를 split()로 단순하게 나누어 토큰화하여 학습한 모델입니다.
