# 요구사항

## G1: FOSS 책임 숙지

### 1.1 Supplied Software 배포의 FOSS License Compliance를 관리하는 서면으로 작성된 FOSS 정책이 최소한 내부 의사 소통 공간에 존재한다.

#### 확인 산출물 (Verification Artifact(s)):
- 1.1.1 문서화된 FOSS 정책이 존재한다.
- 1.1.2 모든 Software Staff이 FOSS 정책의 존재를 인식할 수 있도록 하는 문서화된 절차(예: Traning, 내부 wiki 혹은 기타 실잘직인 의사 소통 방법을 통한)가 존재한다.

#### 설명:
FOSS 정책을 생성 및 기록하고 이를 Software Staff이 인식하게 할 수 있는 조치가 취해졌는지 확인하라. 여기서는 정책 내에 무엇이 포함되어야만 하는지에 대해서는 요구하고 있지 않지만, 다른 섹션에서는 다른 요구사항이 있을 것이다.


### 1.2 모든 Software Staff 대상으로 다음과 같은 필수 FOSS Training이 존재한다. 
- Training은 최소한 다음 주제를 다룬다. 
  - FOSS 정책 및 사본을 찾을 수 있는 곳;
  - FOSS 및 FOSS License에 관한 IP 법의 기본;
  - FOSS Licensing 개념 (Permissive 및 Copyleft 개념 포함);
  - FOSS Project Licensing 모델;
  - 세부적인 FOSS Compliance 및 전반적인 FOSS 정책에 관한 Software Staff 역할 및 책임과; 
  - Supplied Software에 포함된 FOSS Component의 식별, 기록 및 추적을 위한 Process;
  - Software Staff은 지난 24개월(현재로 간주됨)내 FOSS Training을 완료해야 한다. Test를 통해 Training 요구사항을 만족하는 Software Staff을 확인할 수 있다. 

#### 확인 산출물 (Verification Artifact(s)):
- 1.2.1 위의 주제를 다루는 FOSS 과정 자료(예: 슬라이드 자료, Online 과정 혹은 다른 Training 자료)가 존재한다.
- 1.2.2 모든 Software Staff이 과정을 완료하였는지 추적하는 방법
- 1.2.3 적어도 Software Staff의 85%가 현재 (위에서 정의한) 완료한 상태

#### 설명:
Software Staff이 최근 FOSS Training에 참석했는지, FOSS Training이 핵심 FOSS 주제를 다루는지를 확인한다. 이 의도는 핵심 기본 수준의 주제를 다루는 것이지만, 일반적인 Training Program은 여기서 요구하는 것 보다 더 포괄적일 수도 있다. 

## G2: Compliance 달성을 위한 책임 할당
### 2.1 FOSS 연락담당자(Liaison)의 기능을 확인한다. 
- FOSS 관련 외부 문의 대응을 책임질 인원을 지정한다. 
- FOSS 연락담당자는 타당한 FOSS Compliance 문의에 대응하기 위해 상업적으로 합당한 노력을 해야한다. 그리고,
- 전자 통신을 통해 FOSS 연락담당자에게 연락할 수 있는 방법이 공개되어있는지 확인해야 한다. 

#### 확인 산출물 (Verification Artifact(s)):

- 2.1.1 FOSS 연락담당자 기능이 공개적으로 확인된다. (예: Email 주소 혹은 Linux Foundation의 Open Compliance Directory를 통해)
- 2.1.2 FOSS Compliance 문의를 대응하기 위한 책임을 할당하는 문서화된 절차가 존재한다. 

#### 설명:
제3자가 FOSS Compliance 문의와 관련하여 조직에 연락할 수 있는 합리적인 방법이 있는지 확인한다. 

### 2.2 내부 FOSS Compliance 담당을 확인한다. 

- 내부 FOSS Compliance를 관리할 인원을 지정한다. FOSS Compliance 담당과 FOSS 연락담당자는 동일 인원이 될 수 있다.
- FOSS Compliance 관리 활동에는 충분한 자원이 있다. 
  - 담당자로서 역할을 수행할 시간이 할당되고, 
  - 상업적으로 합당한 예산이 배정된다. 
- FOSS 정책 및 Process를 개발하고 유지할 책임을 할당한다.  
- FOSS Compliance 담당은 FOSS Compliance에 대한 (내외부) 법률 전문 지식에 접근 가능하다. 
- FOSS Compliance 이슈의 해결을 위한 Escalation이 가능하다. 

#### 확인 산출물 (Verification Artifact(s)):
- 2.2.1 지정된 FOSS Compliance 담당자, 조직 혹은 직무 이름
- 2.2.2 FOSS Compliance 담당이 사용할 수 있는 법률 전문 지식의 제공처를 확인한다. 
- 2.2.3 FOSS Compliance에 대한 책임을 할당할 수 있는 문서화된 절차가 존재한다. 
- 2.2.4 이슈 해결을 위한 Escalation 경로를 확인하는 문서화된 절차가 존재한다. 

#### 설명: 
FOSS 책임이 효과적으로 할당되었는지 확인한다. 

## G3: FOSS Content Review 및 승인

### 3.1 Supplied Softtware가 포함하는 모든 FOSS Component(및 각각 식별된 License)를 확인, 추적 및 보관하는 Process가 존재한다.  

#### 확인 산출물 (Verification Artifact(s)):
- 3.1.1 Supplied Software가 포함하는 FOSS Componnet 및 식별된 License 목록을 확인, 추척, 보관하는 문서화된 절차가 존재한다. 

#### 설명: 
Supplied Software를 구성하는 모든 FOSS Component를 확인하고 나열하기 위한 Process가 존재하는지 확인한다. 이 목록표는 Supplied Software에 적용되는 각각의 배포 의무 및 제한사항을 이해하기 위해 각 Component의 License 조항을 체계적으로  Review할 수 있도록 존재해야 한다. 또한 이 기록된 목록표는 Process가 수행되었다는 증빙으로 사용된다. 

### 3.2 FOSS Program은 Supplied Software에 대해 Software Staff이 접하게 되는 일반적인 FOSS Use Case를 처리할 수 있어야 하고, 여기에는 다음과 같은 Use Case가 포함될 수 있다. - (아래 리스트가 총망라한 것은 아니고, 조직에 따라 아래의 모든 사항이 적용되는 것도 아닌 것에 유의) Supplied Software의 일부가 :   
- Binary Form으로 배포되는 경우 
- Source Form으로 배포되는 경우
- 다른 FOSS와 통합되어 Copyleft 의무 사항을 유발시키는 경우
- 수정한 FOSS를 포함하는 경우
- FOSS 혹은 Supplied Sofware내 다른 Component와 상호 작용하면서 호환되지 않는 License하에 있는 다른 Software를 포함하는 경우
- 저작자 표시 요구사항이 있는 FOSS를 포함하는 경우

The FOSS program must be capable of handling typical FOSS use cases encountered by Software Staff for Supplied Software, which may include the following use cases - when parts of the Supplied Software (note that the below list is neither exhaustive, nor may all of the below use cases apply depending on the organization): are distributed in binary form


## G4: FOSS Content 문서 및 산출물 제공

## G5: FOSS Community 참여 이해

## G6: OpenChain 요구사항 준수 인증
