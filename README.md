# Teste de Ransomware para Criptografia de Arquivos

Este repositório contém um **teste de ransomware** que foi desenvolvido com o objetivo de **demonstrar a criptografia de arquivos**. O código foi criado para fins **educacionais e de pesquisa** apenas, e NÃO deve ser utilizado de forma maliciosa ou em sistemas de produção.

⚠️ **Aviso Importante:** O uso deste código em sistemas reais pode resultar na perda permanente de dados. Utilize somente em ambientes controlados, como máquinas virtuais, e sempre com backups adequados.

## Descrição

Este projeto simula o comportamento de um ransomware, criptografando arquivos em um diretório específico. Ele pode ser usado para entender como as técnicas de criptografia e ataques de ransomware funcionam em um nível básico, mas **não é uma implementação de um ransomware real**.

### Funcionalidades


- Simula o comportamento de um ataque de ransomware sem causar danos reais, em um ambiente controlado.
- Permite a reversão da criptografia utilizando uma chave de descriptografia.



## Como Usar

Copie o repositório ou baixe os arquivos em sua máquina

Instale a lib pyaes com o pip:

```bash
  pip install pyaes
```

Para criptografar o arquivo utilize o comando:

```bash
python3 encrypter.py
```

Verifique o arquivo gerado ".ransomwaretroll", este terá os dados criptografados.

![Image](https://github.com/user-attachments/assets/d04ff6c9-4e71-41fe-9c6f-698d1506b8b5)

Para descriptografar o arquivo utilize o comando:

```bash
python3 decrypter.py
```

![Image](https://github.com/user-attachments/assets/a5c5850a-f619-4adc-9e82-6902e3a2ffb5)



