### 2.5.1    볼륨 추가

볼륨을 추가하여 사용할 수 있습니다.

##### a\)    환경설정 -&gt; 서비스 -&gt; 오른쪽 상단 + 모양의 버튼 클릭![](/image.kh/image.kh/볼륨 추가1.png)

##### b\)    클러스터, 이름, 설명, 정책을 차례로 기입합니다.![](/image.kh/image.kh/볼륨추가2.png)

| **정책** | **설명** |
| :--- | :--- |
| Retain | PersistentVolumeClaim\(PVC\)가 삭제되도 PersistentVolume\(PV\)안에 데이터가 남아있으며 데이터 이동 후 PV를 재사용 할 수 있습니다 |
| Recycle | 적절한 volume plugin이 있다면 사용한 PV가 다시 새로운 Claim을받을 수 있도록 만들어 줍니다. |
| Delete | PVC가 삭제되면서 해당 PV도 함께 삭제되고 그안의 데이터도 모두 삭제됩니다. |

##### 

##### c\) 사용하는 스토리지 플러그인에 따라 스토리지 클래스와 파라미터 설정을 해줍니다.

* ##### NFS 스토리지 플러그인 사용 시![](/assets/nfs.png)

| 스토리지 플러그인 | Network File System |
| :--- | :--- |
| 스토리지 클래스 이름 | cocktail-nfs 고정 값 |
| 파라미터 | path : NFS server 의 공유폴더 경로                              server : NFS server 의 IP |

.

.

* **아마존 스토리지 플러그인 사용 시**![](/assets/aws.png)

| 스토리지 플러그인 | AWS EBS \(아마존 사의 스토리지 서비스\) |
| :--- | :--- |
| 스토리지 클래스 이름 | default 고정값 |
| 파라미터 | 파라미터 값 없음 |

.  
.

* **구글 스토리지 플러그인 사용 시**![](/assets/구글.png)

| 스토리지 플러그인 | Google Persistent Disk \(구글 사의 스토리지 서비스\) |
| :--- | :--- |
| 스토리지 클래스 이름 | standard 고정값 |
| 파라미터 | type : 구글 스토리지 클래스의 유형 값                                             zone : 스토리지 생성된 zone 값 |

.

.

* Azure** 스토리지 플러그인 사용 시**![](/assets/azure.png)

| 스토리지 플러그인 | Azure Disk \(마이크로소프트사의 스토리지 서비스\) |
| :--- | :--- |
| 스토리지 클래스 이름 | default 고정값을 가짐. |
| 파라미터 | 파라미터 값 없음 |


