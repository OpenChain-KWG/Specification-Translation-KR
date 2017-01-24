# 요구사항

## G1: FOSS 책임 숙지

### 1.1 문서화된 FOSS 정책이 존재한다. 이로써 Supplied Software 배포 시, FOSS License Compliance를 관리한다. 이는 최소 내부에서 접근할 수 있는 공간에 존재한다. 

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

### 3.2 FOSS Program은 Supplied Software에 대해 Software Staff이 접하게 되는 일반적인 FOSS Use Case를 처리할 수 있어야 하고, 여기에는 다음과 같은 Use Case가 포함될 수 있다. - (아래 리스트가 모든 경우를 포함하지는 않으며 또한, 조직에 따라 아래의 모든 사항이 적용되는 것은 아님) Supplied Software의 일부가 :   
- Binary Form으로 배포되는 경우 
- Source Form으로 배포되는 경우
- 다른 FOSS와 통합되어 Copyleft 의무 사항을 유발시키는 경우
- 수정한 FOSS를 포함하는 경우
- FOSS 혹은 Supplied Sofware내 다른 Component와 상호 작용하면서 호환되지 않는 License하에 있는 다른 Software를 포함하는 경우
- 저작자 표시 요구사항이 있는 FOSS를 포함하는 경우

#### 확인 산출물 (Verification Artifact(s)):
- 3.2.1 Supplied Software에 대해 Software Staff이 접할 수 있는 일반적인 FOSS Use Case를 처리할 수 있는 Process가 구현되었다. 

#### 설명: 
조직의 사업 실무 결과에 따른 조직의 일반적인 Use Case를 해결하기에 충분히 탄탄한 FOSS Program을 만든다. 


## G4: FOSS Content 문서 및 산출물 제공

### 4.1 해당하는 식별된 License에서 요구하는대로 Supplied Software와 함께 제공하기 위한 다음의 배포 Compliance 산출물 (Distributed Compliance Artifact)을 준비하라. 여기에는 다음 내용이 포함될 수 있지만, 이에 국한되지는 않는다.: 
- 저작권 고지(Copyright Notices)
- 식별된 License의 사본
- 수정 고지
- 저작자 표시 (Attribution Notices)
- 눈에 띄는 고지
- Source Code
- 요구되는 Build 방법 및 Script
- Written Offer

#### 확인 산출물 (Verification Artifact(s)):
- 4.1.1 식별된 License에서 요구하는대로 Supplied Software와 함께 Distributed Compliance Artifact가 배포되도록 보장하는 Process를 설명하는 문서화된 절차가 존재한다. 

- 4.1.2 Distributed Compliance Artifact의 사본은 보관되고 쉽게 검색할 수 있다 (예: Legal Notice, Source Code, SPDX 문서). 보관된 자료는 적어도 Supplied Software가 제공되는 한 혹은 식별된 License에서 요구하는 기한동안 존재하도록 한다 (둘 중 더 긴 것을 따름). 

#### 설명:
Supplied Software에 적용되는 식별된 License에서 요구하는대로 완전한 Compliance 산출물 집합이 Supplied Software와 함께 제공되는지 확인한다. 

## G5: FOSS Community 참여 이해

### 5.1 조직 대신 직원들이 공개적으로 접근 가능한 FOSS Project에 Contribution하는 것을 관리하는 문서화된 정책이 존재한다. 이는 최소 내부에서 접근할 수 있는 공간에 존재만 한다.


#### 확인 산출물 (Verification Artifact(s)):
- 5.1.1 문서화된 FOSS 기여(Contribution) 정책이 존재한다.;

- 5.1.2 모든 Software Staff이 FOSS 기여(Contribution) 정책의 존재를 알도록 하는 문서화된 절차(예: 교육, 내부 wiki, 혹은 다른 실제적인 의사 소통 방법을 통해)가 존재한다.


#### 설명:
FOSS에 공개적으로 기여(Contribution)하는 것과 관련된 정책 개발에 대해 조직이 합당한 고려를 하였는지 확인한다. 
FOSS 기여(Contribution) 정책은 조직의 전체 FOSS 정책의 일부로 만들수도 있고, 자체적인 별도의 정책으로 만들수도 있다. 기여(Contribution)이 전혀 허용되지 않는 상황이라면, 이를 명확히하는 정책이 있어야 한다. 


### 5.2 FOSS 기여 정책이 기여를 허용하는 경우, 기여가 FOSS 기여 정책을 준수하는지 확인하기 위한 Process가 존재한다. 여기에는 다음과 같은 고려사항이 포함될 수 있지만, 이에 국한되지는 않는다. : 
- 
 legal approval for license considerations
 business rationale or approval
 technical review of code to be contributed
 community engagement and interaction, including a project’s Code of Conduct or
equivalent
 adherence to project-specific contribution requirements
Verification Artifact(s):
 5.2.1 Provided the FOSS contribution policy permits contributions, a documented procedure
exists that describes the FOSS contribution process.
Rationale:
Ensure an organization has a documented process for how the organization publicly contributes
FOSS. A policy may exist such that contributions are not permitted at all. In that specific
situation it is understood that no process may exist and this requirement would nevertheless be
met. 




## G6: OpenChain 요구사항 준수 인증
