# Painel de Vendas TIM

Sistema de gerenciamento de clientes e vendas desenvolvido para a TIM, com funcionalidades de consulta de CNPJ/CEP, bot de conversação e integração planejada com WhatsApp.

## 🚀 Funcionalidades Principais

### Bot de Conversação
- Consulta automática de CNPJ e CEP
- Integração com APIs externas
- Tratamento de erros e estados de carregamento
- Interface visual padronizada TIM
- Histórico de mensagens com rolagem automática

### Gerenciamento de Clientes
- Sistema de cores para diferentes tipos de empresas
- Exibição detalhada de informações
- Funcionalidade expandir/recolher detalhes
- Controle de permissões para edição/exclusão
- Indicadores visuais para empresas inaptas/devedoras

### Sistema de Filtros
- Busca avançada com múltiplos critérios
- Filtro por nome ou CNPJ
- Categorização por tipo de empresa
- Verificação de situação cadastral
- Análise de limite de crédito

### Dashboard Principal
- Integração completa dos componentes
- Gerenciamento de estado (React Query)
- Filtros em tempo real
- Sistema de permissões por nível
- Layout responsivo

## 🛠️ Tecnologias Utilizadas

- Next.js
- TypeScript
- Prisma
- React Query
- Axios
- Tailwind CSS

## 📱 Integração WhatsApp (Planejada)

Funcionalidade planejada utilizando a biblioteca Baileys:
- [ ] Instalação e configuração Baileys
- [ ] Serviço de conexão WhatsApp
- [ ] API para gerenciamento de conversas
- [ ] Interface de usuário para WhatsApp

## 🎨 Interface Visual

- Cores oficiais TIM:
  - Azul marinho: `#00348D`
  - Vermelho: `#E40613`
- Design system padronizado
- Cards com cantos arredondados
- Tipografia consistente
- Sistema de cores para categorização

## ⚠️ Pontos de Atenção

1. **Dependências**: Necessário instalar dependências antes da execução
2. **Recursos Estáticos**: Verificar arquivos de imagem no diretório público
3. **Modais**: Implementação pendente de modais para adição/edição
4. **WhatsApp**: Integração planejada mas não implementada
5. **Imports**: Verificar estrutura de diretórios para imports

## 🚦 Status do Projeto

- ✅ Bot de Conversação
- ✅ Sistema de Cards
- ✅ Filtros de Pesquisa
- ✅ Dashboard Principal
- ✅ API de Integração
- ⏳ Integração WhatsApp

## 🔧 Como Executar

1. Clone o repositório
```bash
git clone https://github.com/valentimdigital/paineldevendas.git
```

2. Instale as dependências
```bash
npm install
```

3. Configure as variáveis de ambiente
```bash
cp .env.example .env
```

4. Execute o projeto
```bash
npm run dev
```

## 📄 Licença

Este projeto é privado e de propriedade da TIM Brasil.

## 👥 Desenvolvido por

[Valentim Digital](https://github.com/valentimdigital) 