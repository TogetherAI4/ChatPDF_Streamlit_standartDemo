# Chat mit PDF

Dieses Repository implementiert einen Chat mit Ihrem PDF über eine grafische Benutzeroberfläche (GUI). Dieser Code verwendet OpenAI's LLM- und Embedding-Modelle zur Informationsgewinnung aus Ihren Dokumenten.

![ChatApp UI](https://github.com/PromtEngineer/PDF_Chat-GUI/assets/134474669/bba57a81-909f-4fe3-91cd-96ae14c17438)

## Repository klonen:
Klonen Sie das Repository.
```shell
git clone https://github.com/PromtEngineer/PDF_Chat-GUI.git

## Umgebung einrichten
Um Ihre Umgebung für die Ausführung des Codes hier einzurichten, installieren Sie zuerst alle Anforderungen:

```shell
pip install -r requirements.txt
```

## OpenAI API-Schlüssel

Sie benötigen den OpenAI API-Schlüssel, um dies auszuführen. Holen Sie sich Ihren OpenAI-Schlüssel von [hier](https://platform.openai.com/account/api-keys).
Setzen Sie in der `.env` Ihren API-Schlüssel ein.

```shell
OPENAI_API_KEY=
```

## Starten der Webanwendung:

```shell
streamlit run ChatPDF.py
```
```
