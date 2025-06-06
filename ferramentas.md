
# 🧰 Ferramentas Essenciais de Cibersegurança

Coloquei algumas ferramentas fundamentais para atuar em diferentes áreas da cibersegurança: **defensiva (Blue Team)**, **ofensiva (Red Team)** e **análise forense**.

> 🔍 Foquei em ferramentas gratuitas, open source e amplamente usadas no mercado.

---

## 🛡️ Blue Team (Defesa, SOC, Monitoramento)

### 📡 Wireshark
- **Função:** Analisador de tráfego de rede (packet sniffer).
- **Uso comum:** Identificar pacotes suspeitos, análise de incidentes.
- **Site:** [https://www.wireshark.org/](https://www.wireshark.org/)

### 🔎 Sysmon + Event Viewer
- **Função:** Monitoramento avançado de eventos no Windows.
- **Uso comum:** Detecção de comportamento malicioso, logs para análise.
- **Docs:** [Sysmon](https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon)

### 🧩 ELK Stack (Elasticsearch, Logstash, Kibana)
- **Função:** Análise e visualização de logs em grande escala.
- **Uso comum:** SIEM caseiro ou comercial.
- **Site:** [https://www.elastic.co/what-is/elk-stack](https://www.elastic.co/what-is/elk-stack)

### 🛠️ Wazuh
- **Função:** SIEM open source com HIDS integrado.
- **Uso comum:** Monitoramento de integridade, detecção de ameaças, resposta a incidentes.
- **Site:** [https://wazuh.com/](https://wazuh.com/)

### 📈 Grafana + Prometheus
- **Função:** Monitoramento de performance e alertas.
- **Uso comum:** NOC/SOC para métricas de infra, logs e detecção de anomalias.
- **Site:** [https://grafana.com/](https://grafana.com/)

---

## 🕵️ Red Team (Ataque Ético, Pentest)

### 🧪 Burp Suite (Community)
- **Função:** Testes de segurança em aplicações web.
- **Uso comum:** Interceptação de requisições, fuzzing e XSS.
- **Site:** [https://portswigger.net/burp](https://portswigger.net/burp)

### 🐙 Nmap
- **Função:** Scanner de redes e portas.
- **Uso comum:** Mapeamento de alvos, detecção de serviços.
- **Site:** [https://nmap.org/](https://nmap.org/)

### 🦊 Metasploit Framework
- **Função:** Plataforma de exploração de vulnerabilidades.
- **Uso comum:** Testes ofensivos e prova de conceito (PoC).
- **Site:** [https://www.metasploit.com/](https://www.metasploit.com/)

### 🐍 Impacket
- **Função:** Scripts para exploração em redes Windows.
- **Uso comum:** Relays, pass-the-hash, Kerberoasting.
- **Repo GitHub:** [https://github.com/SecureAuthCorp/impacket](https://github.com/SecureAuthCorp/impacket)

### 🐚 Kali Linux / Parrot OS
- **Função:** Distros completas para pentesters.
- **Uso comum:** Ambientes prontos com ferramentas pré-instaladas.
- **Sites:** [Kali](https://www.kali.org/), [Parrot](https://www.parrotsec.org/)

---

## 🧪 Análise Forense & Malware

### 🧊 Autopsy
- **Função:** Ferramenta de análise forense de discos.
- **Uso comum:** Recuperação de arquivos, análise de imagens de disco.
- **Site:** [https://www.sleuthkit.org/autopsy/](https://www.sleuthkit.org/autopsy/)

### 🧬 VirusTotal
- **Função:** Scanner de arquivos e URLs com múltiplos antivírus.
- **Uso comum:** Verificação de malware, IOC hunting.
- **Site:** [https://www.virustotal.com/](https://www.virustotal.com/)

### 🧠 Ghidra
- **Função:** Engenharia reversa de binários.
- **Uso comum:** Análise de malware e binários compilados.
- **Site:** [https://ghidra-sre.org/](https://ghidra-sre.org/)

---

## 🔧 Dicas para montar seu ambiente de testes

- ⚙️ Use **máquinas virtuais** com VirtualBox ou VMware para simular redes seguras.
- 🧱 Utilize distros como o queridinho **Kali**.
- 🌐 Crie um lab com **máquinas Windows e Linux** para praticar ataques e defesa.
- 🚫 Nunca teste em ambientes reais sem autorização! Isso é crime, ok?

---

## 📦 Extras e Repositórios Recomendados

- [awesome-cybersecurity](https://github.com/apsdehal/awesome-ctf) – Listas de ferramentas, labs e recursos
- [GTFOBins](https://gtfobins.github.io/) – Exploração de binários comuns em Linux
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) – Cheatsheets para testes ofensivos


---

📁 Voltar para: [`guia-ciberseguranca`](../README.md)
