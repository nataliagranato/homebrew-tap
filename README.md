# Homebrew Tap - Natália Granato

Este é o Homebrew Tap oficial da [@nataliagranato](https://github.com/nataliagranato), contendo fórmulas para instalar facilmente suas ferramentas de linha de comando relacionadas a DevOps, Kubernetes e Cloud Native.

## 🚀 O que é um Homebrew Tap?

Um Homebrew Tap é um repositório de terceiros que contém fórmulas extras para o [Homebrew](https://brew.sh/), o gerenciador de pacotes para macOS e Linux. Este tap permite que você instale facilmente as ferramentas desenvolvidas pela Natália usando o Homebrew.

## 📦 Instalação do Tap

Para adicionar este tap ao seu Homebrew:

```bash
brew tap nataliagranato/tap
```

## 🛠️ Ferramentas Disponíveis

### kubeon
CLI tool para gerenciar RBAC no Kubernetes, definir quotas de namespace e criar arquivos Kubeconfig para usuários.

```bash
brew install nataliagranato/tap/kubeon
```

**Funcionalidades:**
- Gerenciamento de RBAC no Kubernetes
- Configuração de quotas de namespace
- Criação de arquivos Kubeconfig para usuários
- Simplifica o processo de gerenciamento de permissões e recursos do Kubernetes

### k8s-api-metrics
API de métricas Kubernetes que fornece informações sobre o cluster através de endpoints RESTful protegidos por autenticação.

```bash
brew install nataliagranato/tap/k8s-api-metrics
```

**Funcionalidades:**
- Coleta e exposição de métricas do Kubernetes
- Endpoints RESTful para consulta de métricas
- Autenticação integrada
- Monitoramento de clusters Kubernetes

## 📋 Requisitos

- macOS 10.15+ ou Linux
- [Homebrew](https://brew.sh/) instalado

## 🔄 Atualizando Ferramentas

Para atualizar todas as ferramentas instaladas deste tap:

```bash
brew upgrade nataliagranato/tap/<nome-da-ferramenta>
```

Para atualizar todas as fórmulas do Homebrew:

```bash
brew upgrade
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você encontrar algum problema ou tiver sugestões:

1. Abra uma [issue](https://github.com/nataliagranato/homebrew-tap/issues)
2. Faça um fork do repositório
3. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`)
4. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`)
5. Push para a branch (`git push origin feature/nova-feature`)
6. Crie um Pull Request

## 📖 Sobre a Autora

**Natália Granato** é especialista em tecnologias Cloud Native, containers, Kubernetes, DevOps e observabilidade. 

- 🌟 [GitHub](https://github.com/nataliagranato)
- 💼 [LinkedIn](https://linkedin.com/in/nataliagranato)
- 📝 [Blog](https://nataliagranato.github.io)
- 🗣️ CNCF Ambassador

### Projetos Relacionados

- [k8s-troubleshooting](https://github.com/nataliagranato/k8s-troubleshooting) - Guia de troubleshooting do Kubernetes
- [docker101](https://github.com/nataliagranato/docker101) - Boas práticas na construção de aplicações Cloud Native
- [intensive-terraform](https://github.com/nataliagranato/intensive-terraform) - Guia prático para dominar Terraform

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🆘 Suporte

Se você tiver problemas com alguma ferramenta:

1. Verifique se você tem a versão mais recente: `brew upgrade nataliagranato/tap/<ferramenta>`
2. Consulte a documentação específica da ferramenta no repositório correspondente
3. Abra uma issue neste repositório ou no repositório da ferramenta específica

---

⭐ Se este tap foi útil para você, considere dar uma estrela no repositório!