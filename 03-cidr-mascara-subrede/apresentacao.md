# ATIVIDADE – CIDR E MÁSCARA DE SUB-REDE

> Questionário de múltipla escolha • Redes de Computadores

## 1. O que significa o número após a barra em um endereço IP, como 192.168.1.10/24?

- A) A quantidade de computadores conectados
- B) A quantidade de bits destinados à rede. ✅
- C) A quantidade de roteadores da rede
- D) O número da porta de comunicação

Explicação: O número após a barra indica o tamanho do prefixo CIDR, ou seja, quantos bits do endereço IP são destinados à identificação da rede.

## 2. Qual é a máscara de sub-rede correspondente ao CIDR /8?

- A) 255.255.255.0
- B) 255.255.0.0
- C) 255.0.0.0. ✅
- D) 255.255.255.255

Explicação: O CIDR /8 significa que os primeiros 8 bits são destinados à rede, resultando na máscara 255.0.0.0.

## 3. Qual é a máscara de sub-rede correspondente ao CIDR /16?

- A) 255.255.0.0. ✅
- B) 255.0.0.0
- C) 255.255.255.0
- D) 255.255.255.128

Explicação: O CIDR /16 utiliza 16 bits para identificar a rede, correspondendo a 255.255.0.0.

## 4. Qual máscara corresponde ao CIDR /24?

- A) 255.0.0.0
- B) 255.255.0.0
- C) 255.255.255.128
- D) 255.255.255.0. ✅

Explicação: O CIDR /24 utiliza 24 bits para a rede e deixa 8 bits disponíveis para os hosts.

## 5. Um endereço IPv4 possui quantos bits no total?

- A) 8 bits
- B) 16 bits
- C) 32 bits. ✅
- D) 64 bits

Explicação: Um endereço IPv4 possui 32 bits, divididos em 4 grupos de 8 bits (octetos).

## 6. No endereço 192.168.1.20/24, qual é o endereço da rede?

- A) 192.168.1.20
- B) 192.168.1.0. ✅
- C) 192.168.0.0
- D) 192.168.1.255

Explicação: Com a máscara /24 (255.255.255.0), os três primeiros octetos identificam a rede. Portanto, o endereço da rede é 192.168.1.0.

## 7. No CIDR /24, quantos bits ficam disponíveis para os hosts?

- A) 8 bits. ✅
- B) 16 bits
- C) 24 bits
- D) 32 bits

Explicação: Como o IPv4 possui 32 bits e 24 são utilizados para identificar a rede, sobram 8 bits para os hosts.

## 8. Tradicionalmente, quantos hosts utilizáveis existem em uma sub-rede /24?

- A) 24
- B) 128
- C) 254. ✅
- D) 256

Explicação: Uma sub-rede /24 possui 256 endereços no total. Porém, tradicionalmente, dois são reservados: um para identificar a rede e outro para broadcast. Assim, restam 254 endereços utilizáveis para hosts.

## 9. Qual CIDR corresponde à máscara 255.255.255.128?

- A) /24
- B) /25. ✅
- C) /26
- D) /16

Explicação: A máscara 255.255.255.128 possui 25 bits ligados em 1 na representação binária, correspondendo ao CIDR /25.

## 10. Se uma rede passa de /24 para /26, o que acontece com a quantidade de bits disponíveis para hosts?

- A) Aumenta de 8 para 10
- B) Permanece em 8
- C) Diminui de 8 para 6. ✅
- D) Diminui de 24 para 16

Explicação: Em uma rede /24, existem 8 bits para hosts. Ao passar para /26, são utilizados mais 2 bits para a rede, restando apenas 6 bits para hosts.

