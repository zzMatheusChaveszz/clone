const data = {
  inicio: {
    pergunta: "Em que área posso ajudar?",
    opcoes: ["Portfólio", "Operações", "Jurídico", "Crédito"]
  },
  Portfólio: {
    pergunta: "Sobre Portfólio?",
    opcoes: ["Como abrir um Chamado?", "Teste"],
    respostas: {
      "Como abrir um Chamado?": 
        'Você pode abrir clicando aqui 👉 <a href="https://helpprodutos.supplier.com.br" target="_blank" style="color:#A3D65C;">Abrir Chamado</a>',
      "Teste": 
        'Aqui está um exemplo de imagem:<br><img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/JPEG_example_flower.jpg" width="250" style="margin-top:10px;border-radius:10px;">'
    }
  },
  Operações: {
    pergunta: "Sobre Operações:",
    opcoes: ["Como comprar?", "É seguro?"],
    respostas: {
      "Como comprar?": 
        'Assista ao vídeo explicativo abaixo:<br><iframe width="300" height="170" style="margin-top:10px;border-radius:10px;" src="https://www.youtube.com/embed/dQw4w9WgXcQ" title="Tutorial" frameborder="0" allowfullscreen></iframe>',
      "É seguro?": "É volátil, exige cautela e carteira segura."
    }
  },
  Jurídico: {
    pergunta: "Sobre Jurídico:",
    opcoes: ["Vantagens", "Riscos"],
    respostas: {
      "Vantagens": "Renda mensal isenta de IR para pessoa física.",
      "Riscos": "Vacância e desvalorização dos imóveis."
    }
  },
  Crédito: {
    pergunta: "Sobre Crédito:",
    opcoes: ["Segurança", "Rentabilidade"],
    respostas: {
      "Segurança": "Mais previsível e seguro que renda variável.",
      "Rentabilidade": "Geralmente menor que ações, mas constante."
    }
  }
};
