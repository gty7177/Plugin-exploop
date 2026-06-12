버그 수정 및 안정화

callSyncMethod().get() → runTask() (웹소켓 블로킹 제거)
HttpClient static 재사용 (메모리 누수 방지)
ConcurrentModificationException 수정
pingThread NPE 방지
자동 재연결 (5초 후)
채팅/후원 시스템

ChatReceiveEvent — 채팅 Bukkit 이벤트
DonationReceiveEvent — 후원/구독 Bukkit 이벤트
DonationHandler — 별도 클래스로 로직 분리
구독 메시지도 이벤트 발사
%json-*% 플레이스홀더 (tellraw 호환)
파일 로그 (logs/yyyy-MM-dd.log)
명령어

명령어	설명
/done list [태그]	연결 상태 + 설정 상태
/done stats	누적 통계 (재시작 유지)
/done add	config.yml에도 저장
