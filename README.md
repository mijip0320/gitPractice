# gitPractice

전체수정은 가능할까




branch2has been made!

branch22 again

mainbranch입니다

main again~~



1/27: 메인에선 이렇게 수정함

호호호호호호



## **Container?**

이미지를 실행한 상태이며 추가되거나 변하는 값은 컨테이너에 저장, 가상화 기술 중 하나

가상머신을 사용해 각 마이크로 서비스를 격리하는 기술

- 단 컨테이너 삭제하면 내부 데이터도 함께 삭제되어서 이를 해결하기 위해 볼륨(`Volume`)을 사용
- CPU의 가상화 기술(HVM)을 이용한 KVM(Kernel-based Virtual Machine)과 반가상화(Paravirtualization)방식의 `Xen`이 등장
- 기존 가상화 기술보다 가벼워지고 이식성이 뛰어남
- 기존의 가상머신은 운영체제 위에 하드웨어를 에뮬레이션하고 그 위에 운영체제를 올리고 프로세스를 실행하는 반면에, 도커 컨테이너는 하드웨어 에뮬레이션 없이 리눅스 커널을 공유해서 바로 프로세스를 실행