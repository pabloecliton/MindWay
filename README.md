# 🚀 MindWay

**Um aplicativo integrado de transporte inteligente que revoluciona a mobilidade urbana**

MindWay é uma plataforma completa que reúne diferentes modalidades de transporte em um único aplicativo, permitindo aos usuários encontrar as melhores rotas de acordo com suas necessidades específicas, condições climáticas e preferências de deslocamento.

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![MapLibre](https://img.shields.io/badge/MapLibre-396CB2?style=for-the-badge&logo=maplibre&logoColor=white)

## ✨ Funcionalidades Principais

### 🗺️ **Sistema de Mapas Interativo**
- Visualização em tempo real de diferentes modalidades de transporte
- Interface intuitiva com camadas alternáveis para cada tipo de transporte
- Integração com MapLibre GL para experiência fluida de navegação

### 🚌 **Transporte Público Integrado**
- **Ônibus**: Informações em tempo real sobre linhas, horários e tarifas

### 🚲 **Mobilidade Sustentável**
- Sistema completo de bike sharing
- Localização de estações de bicicletas públicas
- Informações sobre disponibilidade de bicicletas e vagas

### 🚶‍♀️ **Mobilidade Ativa**
- Rotas otimizadas para caminhada
- Integração com outras modalidades para viagens multimodais

### 🌤️ **Inteligência Climática**
- Informações meteorológicas em tempo real
- Índice de qualidade do ar

### 🧭 **Geolocalização Avançada**
- Detecção automática da localização do usuário
- Busca inteligente de endereços

## 🛠️ Tecnologias Utilizadas

### Frontend
- **Angular 20.2.0**: Framework principal para desenvolvimento da aplicação
- **TypeScript**: Linguagem de programação tipada
- **TailwindCSS 4.1.13**: Framework de CSS utilitário para estilização

### Mapeamento
- **MapLibre GL 5.7.3**: Biblioteca de mapas open-source para renderização
- APIs de geolocalização e roteamento

### Ferramentas de Desenvolvimento
- **Angular CLI**: Ferramenta de linha de comando para desenvolvimento

## 🏗️ Arquitetura do Projeto

```
src/
├── app/
│   ├── componentes/           
│   │   ├── alternadorCamadas  # Controle de camadas do mapa
│   │   ├── cartaoRota         # Exibição de informações de rota
│   │   └── formularioBusca    # Interface de busca de rotas
│   └── servicos/             
│       ├── servicoBicicletas  # Gestão do sistema de bike sharing
│       ├── servicoChavesApi   # Gerenciamento de chaves de API
│       ├── servicoClima       # Informações meteorológicas
│       ├── servicoGeolocalizacao # Geolocalização e geocodificação
│       ├── servicoMapa        # Controle do mapa interativo
│       ├── servicoOnibus      # Sistema de transporte público
│       └── servicoRotas       # Cálculo e otimização de rotas
```

## 🚀 Como Executar o Projeto

### Pré-requisitos
- Node.js (versão 18 ou superior)
- Angular CLI

### Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seu-usuario/mindway.git
   cd mindway
   ```
