# Ent-te-Obsidian
snippet entête pour Obsidian

/* H1 - CARRÉ 20% DÉGRADÉ VISIBLE */
h1,
h1.markdown-preview-section,
.cm-header-1,
.markdown-preview-view h1 {
    position: relative !important;
    top: 0 !important;
    width: 100vw !important;
    height: 20vh !important;
    margin-left: calc(-50vw + 50%) !important;
    margin-top: 0 !important;
    margin-bottom: 1em !important;
    padding: 0 !important;

    /* DÉGRADÉ SUR LE FOND DU CARRÉ */
    background: linear-gradient(135deg, #ff6f61, #ff8e53, #ffa726, #101820) !important;
    border: none !important;
    border-radius: 0 !important;
    box-shadow: none !important;

    /* Texte BLANC centré */
    display: flex !important;
    align-items: center !important;
    justify-content: center !important;
    color: #ffffff !important;
    font-family: "Georgia", serif !important;
    font-size: clamp(2em, 6vw, 3.5em) !important;
    font-weight: 700 !important;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5) !important;
}
