# miniOS

miniOS-project/

├── boot/                   # 부트로더 소스 코드  
O   └── boot.asm            # 부트로더 어셈블리 코드, miniOS 기능을 화면에 출력  
O   └── Makefile            # 부팅 시 출력되는 화면을 확인하기 위한 메이크파일

├── include/                # 헤더 파일  
O   └── file_system.h       # 파일 시스템 헤더  
O   └── memory_management.h # 메모리 관리 헤더 파일  
O   └── scheduling.h        # 스케줄링 헤더 파일  
O   └── system.h            # 

├── kernel/                 # 커널 소스 코드  
O   ├── modules             # 커널 모듈
O   └── kernel.c            #
O   └── kernel.o            #
O   └── process.c           #
O   └── system.c            #
O   └── system.o            #

├── Makefile                # 전체 프로젝트 빌드 자동화를 위한 메이크파일  
├── README.md               # 프로젝트 내 폴더 설명 문서
├── minios                  # 
README.md               # 프로젝트 설명 및 사용 방법 문서 
