# Onboarding - Atividade 1: Configuração do Ambiente

Este repositório contém os projetos iniciais configurados para o processo de Onboarding da IntegrAll Tech.

## Versões Instaladas
Conforme validado no ambiente de desenvolvimento:

* **Java JDK:** 17.0.12" 2024-07-16 LTS
* **Node.js:** v20.19.6 (LTS)
* **Flutter:** 3.38.3 • channel stable
* **Maven:** 3.9.11

## Como Executar os Projetos

### 1. Backend (Java/Spring Boot)
* **Diretório:** `/backend`
* **Comando:** Executar a classe `BackendApplication.java` no IntelliJ.
* **Porta:** `8080`
* **Teste:** Acessar `http://localhost:8080/api/health`

### 2. Frontend (React + Vite)
* **Diretório:** `/frontend`
* **Instalação:** `npm install`
* **Execução:** `npm run dev`
* **Porta:** `5173` (Padrão Vite)
* **Teste:** Acessar `http://localhost:5173`

### 3. Mobile (Flutter)
* **Diretório:** `/mobile_app`
* **Execução:** `flutter run`
* **Dispositivo:** Connected devices:
    Windows (desktop) • windows • windows-x64    • Microsoft Windows [versÆo 10.0.26200.7171]
    Chrome (web)      • chrome  • web-javascript • Google Chrome 142.0.7444.176
    Edge (web)        • edge    • web-javascript • Microsoft Edge 142.0.3595.94
    [1]: Windows (windows)
    [2]: Chrome (chrome)
    [3]: Edge (edge)

## Dificuldades Encontradas e Soluções
Durante a configuração, enfrentei um desafio com o **Android SDK** devido ao meu usuário do Windows conter espaços.

## Screenshots
As capturas de tela solicitadas na atividade (IDEs abertas, DBeaver conectado e apps rodando) estão salvas na pasta `/docs` deste repositório.