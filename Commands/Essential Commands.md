# 📌 Essential Ubuntu Commands

### 패키지 관리 (APT)
- 저장소 갱신: \`sudo apt update\`
- 패키지 업그레이드: \`sudo apt upgrade -y\`
- 불필요한 패키지 정리: \`sudo apt autoremove --purge\`

### 시스템 모니터링 & 자원
- 디스크 사용량: \`df -h\`
- 메모리 사용량: \`free -h\`
- 프로세스 점검: \`htop\` 또는 \`top\`

### 서비스 관리 (systemd)
- 서비스 상태: \`systemctl status <service>\`
- 로그 확인: \`journalctl -u <service> -f\`
