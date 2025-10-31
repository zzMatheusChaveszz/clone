/* ======== 🔹 Responsividade (celulares e tablets) ======== */

/* Tablets e telas médias */
@media (max-width: 1024px) {
  #chat {
    margin: 10px 4rem;
    padding: 15px;
  }

  .message {
    max-width: 80%;
    font-size: 15px;
  }

  header h1 {
    font-size: 22px;
  }
}

/* Celulares */
@media (max-width: 768px) {
  #chat {
    margin: 10px 1rem;
    padding: 10px;
  }

  header {
    flex-direction: row;
    justify-content: space-between;
    padding: 8px 12px;
  }

  header img {
    width: 38px;
    height: 35px;
  }

  header h1 {
    font-size: 20px;
  }

  .message {
    font-size: 14px;
    padding: 8px 12px;
    max-width: 85%;
  }

  .options-container {
    gap: 8px;
  }

  button.message.user {
    font-size: 14px;
    padding: 10px;
  }

  #RX580 {
    width: 8rem;
  }
}

/* Celulares pequenos (ex: 320px) */
@media (max-width: 480px) {
  #chat {
    margin: 5px;
    padding: 8px;
  }

  .message {
    max-width: 90%;
    font-size: 13px;
  }

  header h1 {
    font-size: 18px;
  }

  #RX580 {
    display: none; /* Oculta imagem fixa em telas muito pequenas */
  }
}
