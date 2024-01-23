AWS boto3 자격증명, api를 사용해서 비용을 조회 후 이메일로 전달하는 프로젝트
- 매일 전날 비용을 조회해서 메일로 발송
- 금요일마다 최근 일주일의 요금을 합산해서 주간 보고서 메일 발송

설치 패키지 
- pip install boto3
- pip install awscli
- pip install pandas

발송, 수신 이메일의 경우 SES 리소스에서 이메일 인증이 둘 다 되어야 가능 
![image](https://github.com/taeheilee/AWS_Billing_Report/assets/113228649/2b37c388-d0ca-4622-9c87-f9d9fffb0660)


참고: https://medium.com/@TechStoryLines/generate-aws-cost-reports-automatically-using-the-cost-explorer-api-ef472fca4151
