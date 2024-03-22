glosign 관련 업무 분석

![화면 캡처 2024-03-21 140427](https://github.com/Dong-Hyeok-Ing/job_analyze/assets/77386580/39327c12-7e0e-4a7f-babf-2cc48f8d67ed)

![화면 캡처 2024-03-22 160408](https://github.com/Dong-Hyeok-Ing/job_analyze/assets/77386580/56f236e7-e66e-45b1-8731-e30dd51f7b09)

![화면 캡처 2024-03-22 160614](https://github.com/Dong-Hyeok-Ing/job_analyze/assets/77386580/b3c216d3-39e5-40d0-9e84-b42e76c93245)


https://heeyeah.github.io/spring/2020-02-29-web-flux/

implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
implementation 'org.springframework.boot:spring-boot-starter-jdbc'
/*rest api 위한 의존성*/
implementation 'org.springframework.boot:spring-boot-starter-hateoas'
/*자동 문서 생성을 위한거*/
testImplementation 'org.springframework.restdocs:spring-restdocs-mockmvc'
/*스케쥴러 실행을 위한 의존성*/
implementation 'org.springframework.boot:spring-boot-starter-quartz'
implementation 'org.springframework.boot:spring-boot-starter-web'
/*wsdl webservices를 위한 의존성*/
implementation 'org.springframework.boot:spring-boot-starter-web-services'
/*spring framwork5 추가된 모듈*/
implementation 'org.springframework.boot:spring-boot-starter-webflux'
/*Java Object를 XML로 직렬화하고, XML을 Java Object로 역직렬화*/
implementation 'org.glassfish.jaxb:jaxb-runtime'
/*implementation(files(genJaxbDCTManageService.classesDir).builtBy(genJaxbDCTManageService))*/
/*jaxb "com.sun.xml.bind:jaxb-xjc:2.1.7"*/
/*아주 편한거..!!*/
compileOnly 'org.projectlombok:lombok'
/*스케쥴 락*/
implementation group: 'net.javacrumbs.shedlock', name: 'shedlock-spring', version: '4.12.0'
implementation group: 'net.javacrumbs.shedlock', name: 'shedlock-provider-jdbc-template', version: '4.12.0'
