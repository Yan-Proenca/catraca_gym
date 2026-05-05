# 🏋️‍♂️ Sistema de Catraca Inteligente - Tablet Mode

Este projeto é uma interface de controle de acesso para academias, projetada para tablets. O sistema permite que os alunos validem sua entrada via CPF com feedback visual imediato.

---

## 👥 Desenvolvedores
Projeto desenvolvido por:
* **Yan Matheus Proenca Camargo**
* **Emannoel Henrique de Soares Oliveira**

---

## 🚀 Funcionalidades

* **Interface Glassmorphism:** Design moderno com Tailwind CSS, usando efeitos de desfoque e gradientes.
* **Teclado Numérico Otimizado:** Criado para facilitar a digitação em telas touch.
* **Máscara de CPF:** Formatação automática (000.000.000-00) durante a digitação.
* **Validação de Algoritmo:** Verifica o dígito verificador do CPF localmente antes de consultar a API.
* **Feedback por Cores:**
    * 🟩 **Verde:** Acesso Liberado e redirecionamento.
    * 🟧 **Laranja:** Acesso Negado (pendências ou não encontrado).
    * 🟥 **Vermelho:** CPF Bloqueado ou erro de conexão.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura das páginas.
* **Tailwind CSS:** Estilização e responsividade.
* **JavaScript (Vanilla):** Lógica, máscaras e consumo de API.
* **Font Awesome:** Ícones visuais.
* **Google Fonts:** Tipografia "Plus Jakarta Sans".

---

## 📂 Estrutura de Arquivos

O projeto na pasta `academia` contém:
1. `index.html`: Tela principal com o teclado e lógica de acesso.
2. `bem_vindo.html`: Tela de boas-vindas após liberação.

---

## 🔧 Como Executar

1. Mantenha os arquivos `index.html` e `bem_vindo.html` na mesma pasta.
2. Abra o `index.html` no navegador.
3. O sistema consome a API em: `https://academia-backend-nine.vercel.app/catraca`.

---

## 📝 Notas de Versão
> **Versão 2.0**: Implementação de transições suaves e tratamento de status "BLOQUEADO" (HTTP 403).
