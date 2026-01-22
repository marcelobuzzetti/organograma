# Organograma da 2ª Cia Com Mec

Representação estruturada da hierarquia e seções da 2ª Companhia de Comunicação Mecanizada.

```mermaid
graph TB
    CMT[Cap LUIS COUTINO<br/>CMT]
    CMT --> SCMT[1º Ten BONATTI<br/>SCMT/S2]
    
    SCMT --> S1[SEÇÃO S1]
    S1 --> S2[SEÇÃO S2]
    S2 --> S3[SEÇÃO S3]
    S3 --> S4[SEÇÃO S4]
    S4 --> SAUDE[SEÇÃO SAÚDE]
    SAUDE --> APROV[SEÇÃO APROV]
    APROV --> RP[SEÇÃO RP]
    RP --> GARAGEM[SEÇÃO GARAGEM]
    GARAGEM --> ENCMAT[SEÇÃO ENC MAT]
    ENCMAT --> STI[SEÇÃO STI]
    STI --> SALCBDA[SALC BDA]
    SALCBDA --> SPP[SEÇÃO SPP]
    SPP --> SIP[SEÇÃO SIP]
    SIP --> MNTCOM[MNT COM]
    MNTCOM --> ALMOX[ALMOX]
    
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