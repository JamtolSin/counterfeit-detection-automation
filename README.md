# Counterfeit Detection Automation

## 프로젝트 개요
이 프로젝트는 **n8n**과 **AI 기술**을 활용해 온라인 마켓플레이스에서 짝퉁 제품을 탐지하고 자동으로 대응하는 시스템을 제공합니다.

## 기술 스택
- **프론트엔드:** React
- **백엔드:** Node.js, Express
- **데이터베이스:** MongoDB
- **AI 모델:** TensorFlow/Keras
- **크롤링 및 자동화:** n8n, Puppeteer

## 설치 방법
```bash
git clone https://github.com/your-username/counterfeit-detection-automation.git
cd counterfeit-detection-automation
npm install
docker-compose up -d
```

## n8n 권한 문제 해결 방법
n8n 실행 시 권한 문제가 발생할 경우, 아래 명령어로 .n8n 폴더의 권한을 재설정하세요.
```bash
sudo rm -rf ~/.n8n
mkdir ~/.n8n
sudo chown -R 1000:1000 ~/.n8n
sudo chmod -R 755 ~/.n8n
docker-compose up -d
```

## 사용법
- 제품 이미지를 업로드하고 주기적으로 크롤링 결과를 확인하세요.
- 탐지된 짝퉁 제품에 대해 자동으로 알림을 받고 법적 대응 자료를 생성할 수 있습니다.

## 기여 방법
- 이 프로젝트에 기여하고 싶다면 **포크** 후 **PR 요청**을 보내주세요.

## 라이선스
- MIT License

## 폴더 구조
```
/counterfeit-detection-automation
|-- /frontend
|-- /backend
|-- /n8n-workflows
|-- /ai-models
|-- README.md
|-- docker-compose.yml
```

## 이슈 및 기능 요청
- 프로젝트 관련 이슈는 [Issues](https://github.com/your-username/counterfeit-detection-automation/issues)에 등록해주세요.

---

이 구성을 기반으로 GitHub 레포지토리를 생성하고, 개발 및 문서화 작업을 진행할 수 있습니다.

