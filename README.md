# Cocktail Cloud란?

---

칵테일 클라우드는 `올인원 컨테이너 관리 플랫폼(All-in-one Container Management Platform)`이다.

클라우드 사용이 보편화 되면서, 인프라 뿐 아니라 어플리케이션, 서비스 관리에 대한 요구가 높아지고 있다. 과거와 같은 개발, 운영 방식으로는 클라우드의 장점을 활용하기에 한계가 있기 때문이다. 특히 어플리케이션 영역에서는 지속적인 통합 및 배포\(Continuous Integration/Deploy, CI/CD\), 마이그레이션\(Migration\), 멀티/하이브리드 클라우드 구축 등 자동화, 효율화, 통합 관리에 대한 요구가 증가 하고 있다.

컨테이너 기술의 확산은 이러한 맥락에서 당연하다고 할 수 있다. 현재 많은 기업들이 컨테이너 기술을 도입하였고 그 추세는 계속 증가하고 있다. \(참조: [http://redmonk.com/fryan/2017/09/10/cloud- native-technologies-in-the-fortune-100](http://redmonk.com/fryan/2017/09/10/cloud- native-technologies-in-the-fortune-100)\)

컨테이너는 어플리케이션 또는 서비스를 독립되고 실행 가능한 단위로 패키지 화 하는 기술로, 인프라 환경에 관계 없이 동일한 개발, 운영 경험을 제공 한다. 따라서 인프라에서 서비스까지 클라우드 관리를 표준화하고, 개발 및 운영 노력을 절감 할 수 있다. 특히 일관된 환경하에 멀티/하이브리드 클라우드를 관리 할수 있다는 장점을 제공한다.

칵테일 클라우드는 컨테이너의 장점을 클라우드 관리에 적용하여, 개발 및 운영 업무를 효율화 하고 단일 또는 멀티/하이브리드 클라우드 전략 구현을 위한 플랫폼을 제공한다.

칵테일 클라우드의 주요 기능은 다음과 같다

* 코드로 부터 빌드, 배포, 업데이트까지의 파이프라인 자동화
* 워크로드\(서비스\)중심의 컨테이너 관리: 패키징, 수명주기, 자원 등
* 풀 스택 모니터링: 인프라에서 컨테이너까지의 상태 및 자원 모니터링. Alert 관리
* 멀티/하이브리드 클러스터 프로비져닝 및 관리: Baremetal, 프라이빗/퍼블릭 클라우드

# 이건가?{{ envkey }}
---

다음글 : [Cocktail Cloud 구성 개요](/cocktail-cloud-ad6c-c131-ac1c-c694.md)

버전 : {{ book.ko.version }} - {{ ko.version }}

{% include "server.md" %} 