---
layout: post
title:  "VMware, Nutanix, Openstack 제품 비교"
date:   2021-06-10 10:41:09 +0900
categories: cloud
---

# VMware, Nutanix, Openstack 제품 비교

## 1.VMware, Nutanix, Openstack이란
* VMare, Nutanix : 클라우드 컴퓨팅 및 가상화 소프트웨어를 판매하는 기업
* Openstack : 클라우드 운영체제(소프트웨어) 오픈 소스<br/><br/><br/><br/>

## 2. 비교 기준
VMware나 Nutanix는 클라우드 및 가상화에 관련된 다양한 제품을 가지고 있고, 오픈스택은 많은 컴포넌트로 이루어진 소프트웨어이다.

__VMware와 Nutanix는 서버 가상화, 스토리지 가상화, 네트워크 가상화, HCI 레벨에 있는 제품과 이와 비슷한 역할을 하는 Openstackd의 컴포넌트를 함께 비교했다.__<br/><br/><br/><br/>


## 3. VMware 
### 3.1 VMware 계층별 제품 소개  

<table>
    <thead>
        <tr>
            <th>구분</th>
            <th>계층</th>
            <th colspan=3>제품</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=1>클라우드 관리</td>
            <td rowspan=1>프로비저닝/서비스 관리</td>
            <td colspan=3>VMware vRealize Cloud Management</td>
        </tr>
        <tr>
            <td rowspan=3>HCI(하이퍼 컨버지드 인프라)</td>
            <td>프로비저닝</td>
            <td colspan=3>vCenter Server, Dell EMC VxRail</td>
        </tr>
        <tr>
            <td rowspan=2>가상화</td>
            <td>서버 가상화</td>
            <td>스토리지 가상화</td>
            <td>네트워크 가상화</td>
        </tr>
        <tr>
            <td>vSphere</td>
            <td>vSAN</td>
            <td>NSX Data Center</td>
        </tr>
    </tbody>
</table>  



### 3.2 제품별 설명
* vSphere : 가상 머신, 컨테이너 및 Kubernetes 통합 관리 지원 서버 가상화 소프트웨어
* vSAN : 엔터프라이즈급 스토리지 가상화 소프트웨어
* NSX Data Center : 가상 클라우드 네트워크를 구현하여 데이터 센터, 클라우드, 애플리케이션 프레임워크 전반으로 확장할 수 있는 네트워크 가상화 및 보안 플랫폼
* vCenter Server : 중앙 집중식 서버 관리 소프트웨어
* Dell EMC VxRail : VMware 전용 HCI
* vRealize Cloud Management : 데이터 센터에서 클라우드, 엣지까지 애플리케이션, 인프라 및 플랫폼 서비스의 일관된 배포와 운영을 지원<br/><br/><br/><br/>



## 4. Nutanix 
### 4.1 Nutanix 계층별 제품 소개  

<table>
    <thead>
        <tr>
            <th>구분</th>
            <th>계층</th>
            <th colspan=3>제품</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=1>자동화 및 오케스트레이션</td>
            <td rowspan=1>프로비저닝/서비스 관리</td>
            <td colspan=3>Calm, Era, Karbon</td>
        </tr>
        <tr>
            <td rowspan=4>HCI(하이퍼 컨버지드 인프라)</td>
            <td>프로비저닝</td>
            <td colspan=3>Prism</td>
        </tr>
        <tr>
            <td rowspan=2>가상화</td>
            <td>서버 가상화</td>
            <td>스토리지 가상화</td>
            <td>네트워크 가상화</td>
        </tr>
        <tr>
            <td>AHV</td>
            <td>Files, Volumes, Objects</td>
            <td>Flow</td>
        </tr>
        <tr>
            <td>Cloud OS</td>
            <td colspan=3>AOS</td>
        </tr>
    </tbody>
</table>  

### 4.2 제품별 설명
* AOS : Nutanix HCI 플랫폼 운영 체제
* AHV : KVM 기반의 하이퍼바이저
* Files : 파일 스토리지
* Volumes : 블록 스토리지 솔루션
* Objects : 오브젝트 스토리지
* Flow : 포괄적인 가시성, 보안 및 자동화를 제공하는 소프트웨어 정의 네트워크
* Prism : 하나의 콘솔에서 Nutanix HCI 인프라 관리
* Calm : 애플리케이션 라이프사이클 관리 및 클라우드 오케스트레이션
* Era : 데이터베이스 운영 자동화 및 단순화
* Karbon : 엔터프라이즈용 쿠버네티스 관리 솔루션<br/><br/><br/><br/>


## 5. Openstack 
### 5.1 Openstack 계층별 컴포넌트 소개  

<table>
    <thead>
        <tr>
            <th>구분</th>
            <th colspan=4>컴포넌트</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=2>서비스 관리 및 운영</td>
            <td>대시보드</td>
            <td>모니터링</td>
            <td>리소스 최적화</td>
            <td>빌링</td>
        </tr>
        <tr>
            <td>Horizon</td>
            <td>Ceilometer</td>
            <td>Watcher</td>
            <td>Cloudkitty</td>
        </tr>
        <tr>
            <td rowspan=2>프로비저닝</td>
            <td colspan=2>워크로드 프로비저닝</td>
            <td colspan=2>오케스트레이션</td>
        </tr>
        <tr>
            <td colspan=2>Magnum, Sahara</td>
            <td colspan=2>Heat</td>
        </tr>
        <tr>
            <td rowspan=2>가상화</td>
            <td>베어 메탈</td>
            <td>컴퓨트</td>
            <td>스토리지</td>
            <td>네트워킹</td>
        </tr>
        <tr>
            <td>Ironic</td>
            <td>Nova, Zun</td>
            <td>Swift, Cinder, Manila</td>
            <td>Neutron, Octavia, Designate</td>
        </tr>
    </tbody>
</table>  

### 5.2 제품별 설명
* Irnonic : 베어메탈 하이퍼바이저 API
* Nova : 서버 가상화 지원, 여러 가상화 소프트웨어를 제어하며 VM 등을 관리
* Zun : 컨테이너 관리
* Swift : 오브젝트 스토리지
* Cinder : 블록 스토리지
* Manila : Shared File System
* Neutron : 네트워크 서비스(L2, L3, L4, FW, VPN 등)를 지원
* Octavia : 로드 밸런싱
* Designate : DNS 서비스 제공 및 관리
* Magnum : 컨테이너 오케스트레이션 엔진 프로비저닝
* Sahara : 빅데이터 프로세싱 프레임워크 프로비저닝
* Heat : 클라우드 자원 생성 및 관리
* Horizon : 관리자와 사용자들에게 클라우드 기반 자원 배치의 접근, 제공, 자동화를 위한 그래픽 인터페이스 제공
* Ceilometer : 사용량 모니터링
* Watcher : 리소스 최적화
* Cloudkitty : 과금 정책 관리
<br/><br/><br/><br/>


