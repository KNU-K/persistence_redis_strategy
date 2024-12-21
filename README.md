# REDIS FAILURE HANDLING STRATEGIES
<div align="center">
<img src="https://github.com/user-attachments/assets/c347e9fd-2635-435b-97a8-2a372071d83d" width="270px"/>
</div>

# 서론
Redis는 높은 성능과 간단한 설계 덕분에 널리 사용되는 인메모리 데이터 저장소입니다. 그러나 장애 발생 시 데이터 손실이나 서비스 중단을 방지하기 위해 적절한 장애 처리 전략이 필요합니다. 이 레포지토리는 Redis의 **장애 처리 전략**을 실험하고 학습하기 위한 환경을 제공합니다.

이 프로젝트의 주요 목적은 다음과 같습니다:
1. **Replication (복제)**: Redis Master와 Replica 간의 데이터 복제를 설정하여 데이터 가용성을 높이는 방법을 학습합니다.
2. **Failover (자동 장애 복구)**: Sentinel을 사용하여 Master 장애 시 Replica를 새 Master로 승격하는 과정을 테스트합니다.
3. **High Availability (고가용성)**: Redis의 고가용성을 보장하는 구성 요소들을 탐구하고 이를 실제로 구현합니다.

이를 통해 Redis의 기본 동작 방식뿐만 아니라 복잡한 장애 시나리오에서 어떻게 서비스 연속성을 유지할 수 있는지 실습하고 이해할 수 있습니다.
