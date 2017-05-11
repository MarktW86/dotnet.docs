---
summary: Initializes a new instance of the <xref href="System.Speech.Recognition.SpeechRecognitionEngine"></xref> class.
remarks: "You can construct a <xref:System.Speech.Recognition.SpeechRecognitionEngine> instance from any of the following:  \n  \n-   The default speech recognition engine for the system  \n  \n-   A specific speech recognition engine that you specify by name  \n  \n-   The default speech recognition engine for a locale that you specify  \n  \n-   A specific recognition engine that meets the criteria that you specify in a <xref:System.Speech.Recognition.RecognizerInfo> object.  \n  \n Before the speech recognizer can begin recognition, you must load at least one speech recognition grammar and configure the input for the recognizer.  \n  \n To load a grammar, call the <xref:System.Speech.Recognition.SpeechRecognitionEngine.LoadGrammar%2A> or <xref:System.Speech.Recognition.SpeechRecognitionEngine.LoadGrammarAsync%2A> method.  \n  \n To configure the audio input, use one of the following methods:  \n  \n-   <xref:System.Speech.Recognition.SpeechRecognitionEngine.SetInputToAudioStream%2A>  \n  \n-   <xref:System.Speech.Recognition.SpeechRecognitionEngine.SetInputToDefaultAudioDevice%2A>  \n  \n-   <xref:System.Speech.Recognition.SpeechRecognitionEngine.SetInputToNull%2A>  \n  \n-   <xref:System.Speech.Recognition.SpeechRecognitionEngine.SetInputToWaveFile%2A>  \n  \n-   <xref:System.Speech.Recognition.SpeechRecognitionEngine.SetInputToWaveStream%2A>"
uid: System.Speech.Recognition.SpeechRecognitionEngine.#ctor*
---