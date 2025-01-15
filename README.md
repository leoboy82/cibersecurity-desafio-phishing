```markdown
# Phishing para Captura de Senhas do Facebook

## ⚠️ Aviso Legal  
Este projeto tem finalidade exclusivamente educacional e para conscientização sobre segurança cibernética. O uso deste material para atividades ilícitas é estritamente proibido e pode acarretar consequências legais severas. **Use com responsabilidade.**

---

## 📋 Ferramentas Necessárias  
1. **Kali Linux**  
2. **setoolkit**  

---

## 🔧 Configuração do Phishing no Kali Linux  

### 1️⃣ Acessando o Kali Linux como root  
Execute o comando abaixo para acessar como superusuário:  
```bash
sudo su
```

### 2️⃣ Iniciando o Setoolkit  
Execute o comando para iniciar a ferramenta:  
```bash
setoolkit
```

### 3️⃣ Escolhendo o Tipo de Ataque  
- Selecione a opção: `Social-Engineering Attacks`

### 4️⃣ Definindo o Vetor de Ataque  
- Escolha a opção: `Web Site Attack Vectors`

### 5️⃣ Escolhendo o Método de Ataque  
- Selecione: `Credential Harvester Attack Method`

### 6️⃣ Configurando o Site Cloner  
- Escolha o método: `Site Cloner`  

### 7️⃣ Obtendo o Endereço da Máquina  
Execute o comando para obter o IP da sua máquina:  
```bash
ifconfig
```

Anote o endereço IP exibido.

### 8️⃣ Clonando a URL do Facebook  
Digite a URL para clonagem:  
```plaintext
http://www.facebook.com
```

---

## ⚠️ Observações Importantes  
- **Teste em ambiente controlado**: Certifique-se de realizar testes somente em redes e sistemas sob sua propriedade ou com autorização explícita.  
- **Proteção de terceiros**: Não utilize este método para capturar informações de usuários sem consentimento.  
- **Conscientização**: O objetivo principal é entender como essas técnicas funcionam para implementar contramedidas e proteger-se contra ataques semelhantes.

---

## 📘 Referências  
- [Kali Linux Documentation](https://www.kali.org/docs/)  
- [SET Toolkit Official Documentation](https://github.com/trustedsec/social-engineer-toolkit)  

---

### 🚨 Reforce a Segurança:  
- Não compartilhe este material com pessoas que possam usá-lo de forma inadequada.  
- Sempre denuncie práticas de phishing para as autoridades competentes.

---
```

Este README está organizado e apresenta as informações de forma sistemática e transparente, com seções bem definidas para facilitar o entendimento e navegação. Ele também inclui avisos legais e boas práticas para conscientização e uso responsável.
