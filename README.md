# Auditoria de Força-Bruta — Ambiente Controlado

## 🎯 Objetivo
Realizar um exercício prático em laboratório isolado para compreender ataques de força-bruta em serviços **FTP, Web e SMB**, utilizando ferramentas de auditoria de segurança de forma ética e controlada.

---

## 🧠 Conceitos principais
- **Força-bruta:** técnica que tenta várias combinações de senhas para obter acesso.
- **Autenticação:** processo de verificar a identidade de um usuário.
- **Mitigação:** medidas para reduzir ou impedir ataques desse tipo.

---

## ⚙️ Ambiente de Teste
- Sistema operacional: **Kali Linux**
- Ferramenta de auditoria: **Medusa**,**Hydra**, **Patator**, **Burpsuite**
- Alvos: **VMs vulneráveis (FTP, Web e SMB)** em **rede isolada**
- Todas as ações foram feitas **com autorização** e **sem impacto externo**

---

## 🧩 Metodologia (resumida)
1. **Planejamento:** definição das VMs e contas de teste.  
2. **Reconhecimento:** identificação de serviços ativos.
<img width="1346" height="685" alt="image" src="https://github.com/user-attachments/assets/f77839b3-af4a-412d-9f55-b108d1bbcfd5" />

4. **Execução controlada:** simulação de tentativas automáticas de autenticação.  
5. **Coleta de evidências:** registros e prints das respostas dos serviços.  
6. **Análise e mitigação:** avaliação dos resultados e sugestões de defesa.

---

## 🛡️ Recomendações
1. Implementar **bloqueio temporário** após falhas consecutivas.  
2. Aplicar **rate limiting** por IP e por usuário.  
3. Utilizar **autenticação multifator (MFA)**.  
4. Exigir **senhas fortes** e monitorar logs de login.  
5. Empregar **WAF** ou proteções de borda para endpoints web.

---

## 🗂️ Estrutura do Repositório
