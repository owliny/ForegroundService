# ForegroundService
포어그라운드 서비스와 백그라운드 서비스는 실행 구조를 기준으로 분류합니다.
기본적으로 서비스는 모두 백그라운드 서비스입니다.
여기서 백그라운드란 '화면에 나타나지 않는다'는 의미이고, 백그라운드 스레드처럼 다른 스레드에서 동시 처리되는 것과는 다른 개념입니다.
포어그라운드 서비스는 사용자에게 알림을 통해 현재 작업이 진행 중이라는 것을 알려줘야 합니다.
백그라운드 서비스는 안드로이드 앱이 꺼지거나 안드로이드의 가용 자원이 부족하면 시스템에 의해 제거될 수 있습니다.
포어그라운드 서비스는 사용자가 알림을 통해 서비스가 동작하고 있다는 것을 인지하고 있기 때문에 가용 자원 부족과 같은 이유로는 종료되지 않습니다.
포어그라운드 서비스를 사용하기 위해서는 서비스를 먼저 생성한 후 시스템에 포어그라운드로 사용된다는 것을 알려줘야 합니다.
출처: 이것이 안드로이드다,고돈호 지음, 한빛미디어
