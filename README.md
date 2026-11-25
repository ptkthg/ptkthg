# Patrick Santos

**Security Engineering · DFIR · IAM** — Rio de Janeiro, Brasil

Analista de Segurança da Informação com base em resposta a incidentes, operações de SOC e gestão de identidades.
Hoje escrevo controles de segurança como código: infraestrutura, pipelines e detecções versionadas, testadas no CI
e revisadas antes de chegar à produção.

🔗 [Portfólio](https://portfolioptk.vercel.app) · [LinkedIn](https://www.linkedin.com/in/ptkthg/) · ptkamp1@gmail.com

## Projetos em destaque

| Projeto | O que é | Prova |
|---|---|---|
| [**Perito**](https://github.com/ptkthg/perito) | Kit de resposta a incidentes: normaliza evidências de 7 fontes (Defender, Sentinel, Entra ID, Splunk, Elastic, Wazuh) numa timeline única com custódia SHA-256 e MITRE ATT&CK, até o relatório executivo | [Demo com tour guiado](https://perito-demo-lovat.vercel.app) · 178 + 79 testes no CI |
| [**KQL Detection as Code**](https://github.com/ptkthg/kql-detection-as-code) | Detecções KQL para o Defender XDR, cada uma com teste positivo e negativo executado no emulador oficial do Kusto | 69 testes no CI · camada do ATT&CK Navigator |
| [**Terraform GitHub Seguro**](https://github.com/ptkthg/terraform-github-seguro) | Módulo Terraform que cria repositórios do GitHub já protegidos (secret scanning, push protection, ruleset, Dependabot) | 10 testes com mock_provider · TFLint · Checkov |
| [**SecIdentity AI**](https://github.com/ptkthg/secidentity-ai) | Plataforma multi-agente de IAM/PAM: break-glass no CyberArk, mitigação de SoD e auditoria SOX/ISO 27001 | 3/3 cenários · pacote de auditoria com Merkle e RFC 3161 |
| [**Deception Loop**](https://github.com/ptkthg/deception-loop) | Arquivos-isca e feeds de IOC viram regras YARA e bloqueios de firewall automaticamente | [Demo](https://deception-loop.streamlit.app) · 211 testes |
| [**Perimeter Defend Lab**](https://github.com/ptkthg/perimeter-defend-lab) | Laboratório de perímetro com OPNsense, Wazuh e Suricata; tuning que zerou falsos positivos sem silenciar ataques | Capturas do Wazuh e do tuning |

Também: [Statecraft Cyber](https://statecraftcyber.vercel.app) (threat intelligence em PT-BR) e
[IOC Enricher](https://iocenricher.vercel.app) (enriquecimento de IOCs com OSINT e IA).

## Como trabalho
- **Evidência antes de conclusão:** separo fato observado, hipótese e limitação, e toda afirmação aponta para a fonte.
- **Segurança como código:** o que é configuração vira código revisável, com testes e CI.
- **IA com revisão:** uso Claude Code e Codex com specs e revisão cruzada; as decisões e a metodologia são minhas.

## Ferramentas
- **No trabalho:** Microsoft Defender XDR, Splunk, Google SecOps, Wazuh, Graylog, Entra ID, Active Directory, CyberArk, KQL, Python, PowerShell
- **Nos projetos:** Terraform, GitHub Actions, Checkov, emulador Kusto, React e TypeScript
