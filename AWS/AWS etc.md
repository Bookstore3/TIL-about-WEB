AWS가 제공하는 '심플아이콘'

<a href = "https://aws.amazon.com/ko/architecture/icons/">

AMI 아마존 머신 이미지 : 즉시 사용이 가능한 상태의 OS 및 패키지의 조합

#### Scale

<img src = "../images/scale.pnh">



#### 과금

- EC2 인스턴스는 중지해도 유지하는 용량만큼 청구됨.
- EC2 인스턴스 설정 화면에서 Terminate -> Enable termination protection을 무효화 시킨 후 삭제
- EBS, EC2에서 분리하여 유지하더라도 비용 청구 필요없으면 삭제
- EIP, EC2에 연결 되어 있을 때는 과금되지 않지만, 연결되어 있지 않으면 과금됨 (Release Addresses)
- Route 53은 DNS 존 단위로 월정액 과금
- VPC는 연결 및 데이터 전송에 비용 발생, 유지 자체는 비용이 청구 되지 않음



#### 리소스를 유연하게 변경하기





'Instance Setting' -> 'Change Instane Type' ....



