# Organograma da 2ª Cia Com Mec

Representação estruturada da hierarquia e seções da 2ª Companhia de Comunicação Mecanizada.

```mermaid
graph TD
    CMT[Cap LUIS COUTINO<br/>CMT]
    
    CMT --> SCMT[1º Ten BONATTI<br/>SCMT/S2]
    
    CMT --> S1[SEÇÃO S1]
    CMT --> S2[SEÇÃO S2]
    CMT --> S3[SEÇÃO S3]
    CMT --> S4[SEÇÃO S4]
    CMT --> SAUDE[SEÇÃO SAÚDE]
    CMT --> APROV[SEÇÃO APROV]
    CMT --> RP[SEÇÃO RP]
    CMT --> GARAGEM[SEÇÃO GARAGEM]
    CMT --> ENCMAT[SEÇÃO ENC MAT]
    CMT --> STI[SEÇÃO STI]
    CMT --> SALCBDA[SALC BDA]
    CMT --> SPP[SEÇÃO SPP]
    CMT --> SIP[SEÇÃO SIP]
    CMT --> MNTCOM[MNT COM]
    CMT --> ALMOX[ALMOX]
    
    S1 --> S1_1[2º Ten MASTROPAOLO]
    S1 --> S1_2[1º Sgt FERREIRA]
    S1 --> S1_3[1º Sgt SALVADOR]
    S1 --> S1_4[3º Sgt VERAS]
    S1 --> S1_5[3º Sgt BITTENCOURT]
    S1 --> S1_6[3º Sgt NASCIMENTO]
    
    S2 --> S2_1[1º Sgt SOUZA]
    S2 --> S2_2[3º Sgt LARA]
    
    S3 --> S3_1[2º Ten MALTA]
    S3 --> S3_2[1º Sgt DINIZ]
    S3 --> S3_3[3º Sgt HAKME]
    S3 --> S3_4[3º Sgt EDER]
    
    S4 --> S4_1[1º Ten DOS SANTOS]
    S4 --> S4_2[3º Sgt COUTO]
    S4 --> S4_3[3º Sgt ARTUR]
    
    SAUDE --> SAUDE_1[2º Ten NETO]
    SAUDE --> SAUDE_2[2º Ten NISHIMURA]
    SAUDE --> SAUDE_3[3º Sgt MILATO]
    
    APROV --> APROV_1[1º Ten ROSA]
    APROV --> APROV_2[1º Sgt CAMBRAIA]
    APROV --> APROV_3[3º Sgt GARUZI]
    APROV --> APROV_4[3º Sgt BENTO]
    
    RP --> RP_1[S Ten CARLOS GOMES]
    RP --> RP_2[2º Sgt RIELLA]
    
    GARAGEM --> GARAGEM_1[1º Sgt LEANDRO]
    GARAGEM --> GARAGEM_2[3º Sgt ESPERANCA]
    
    ENCMAT --> ENCMAT_1[1º Sgt MIYASHIRO]
    ENCMAT --> ENCMAT_2[3º Sgt PEREIRA]
    
    STI --> STI_1[2º Sgt VINICIUS LIMA]
    STI --> STI_2[3º Sgt DIONISIO]
    STI --> STI_3[3º Sgt SARAGOSSA]
    
    SALCBDA --> SALCBDA_1[2º Sgt ERIVELTON]
    
    SPP --> SPP_1[2º Sgt GONZALEZ]
    SPP --> SPP_2[3º Sgt BANHARA]
    
    SIP --> SIP_1[3º Sgt FABIO BARBOSA]
    
    MNTCOM --> MNTCOM_1[3º Sgt CARVALHO]
    
    ALMOX --> ALMOX_1[3º Sgt ITALO SILVA]
    
    style CMT fill:#ff9999
    style SCMT fill:#ffcc99
```