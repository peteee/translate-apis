# translate-apis
...testing different translation APIs

this small web-app can also speak the translated words/texts :D

    //SPEECH
    let utterance = new SpeechSynthesisUtterance(speakThis);
    var myLang = utterance.lang;
    utterance.lang = 'es-ES';
    speechSynthesis.speak(utterance);

#APIs
- Google Translate via RAPID API
- Microsoft Translator/Bing Translation via RAPID APi