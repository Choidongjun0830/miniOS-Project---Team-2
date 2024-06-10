# miniOS

miniOS-project/  
├── README.md               # 프로젝트 설명 및 사용 방법 문서  
├── 
├── boot/                   # 부트로더 소스 코드  
O   └── boot.asm            # 부트로더 어셈블리 코드, miniOS 기능을 화면에 출력  
O   └── Makefile            # 부팅 시 출력되는 화면을 확인하기 위한 메이크파일
├── kernel/                 # 커널 소스 코드  
O   ├── modules             # 커널 모듈
O   └── kernel.c            #
O   └── kernel.o            #
O   └── process.c           #
O   └── system.c            #
O   └── system.o            #
├── include/                # 헤더 파일  
O   ├── kernel.h            # 커널 관련 공통 헤더  
O   ├── drivers/            # 드라이버 헤더 파일  
O   └── lib/                # 라이브러리 헤더 파일  
└── scripts/                # 빌드 및 유틸리티 스크립트  
O   ├── minios              # 
O   └── README.md           # 프로젝트 내 폴더 설명 문서
O   └── Makefile            # 전체 프로젝트 빌드 자동화를 위한 메이크파일  
