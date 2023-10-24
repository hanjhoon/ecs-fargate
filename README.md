# ecs-fargate
ecs-fargate 공부


## [Amazon Elastic Container Service](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/developerguide/Welcome.html)

## [AWS Fargate](https://docs.aws.amazon.com/ko_kr/AmazonECS/latest/userguide/what-is-fargate.html)

## ECS
+ Elastic Container Service (ECS)는 컨테이너 오케스트레이션 서비스로, 사용자가 EC2 인스턴스를 직접 관리하고 컨테이너를 실행할 수 있게 해줍니다. 이것은 기존의 EC2 인스턴스를 사용하여 컨테이너를 실행하려는 경우에 유용합니다.

## Fargate
+ AWS Fargate는 서버리스 컨테이너 서비스로, EC2 인스턴스를 관리하지 않고 컨테이너를 실행할 수 있게 해줍니다. Fargate를 사용하면 컨테이너를 실행할 때 EC2 인스턴스를 관리하거나 설정할 필요가 없으며, 컨테이너 당 사용한 리소스만 지불하게 됩니다. 이것은 서버리스 환경을 원하고자 하는 경우 또는 인프라 관리에 대한 부담을 줄이고자 하는 경우에 유용합니다.

## ECS와 Fargate를 함께 사용하는 경우
+ 프로젝트 또는 애플리케이션의 요구 사항에 따라 컨테이너 실행 방식을 선택할 수 있습니다. 일부 애플리케이션 컴포넌트는 ECS를 통해 EC2 인스턴스에서 실행하고, 다른 컴포넌트는 Fargate를 사용하여 서버리스로 실행할 수 있습니다. 이것은 애플리케이션의 유연성과 비용 효율성을 높일 수 있습니다.

## EC2와 Fargate

![image](https://github.com/hanjhoon/ecs-fargate/assets/121271030/5cb0bc9b-c3bd-4e3b-80ab-c103fe8c7131)


