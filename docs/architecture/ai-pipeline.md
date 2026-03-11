# KI‑Verarbeitungspipeline

LexVision 2.0 verwendet eine **Retrieval-Augmented Generation (RAG)**‑Architektur.

## Pipeline

OCR → Textextraktion → Embedding‑Generierung → Vektorsuche (FAISS) → LLM‑Analyse

## Erklärung

1. Dokumente werden hochgeladen und per OCR verarbeitet.
2. Der extrahierte Text wird in Vektor‑Embeddings umgewandelt.
3. Die Embeddings werden in FAISS gespeichert.
4. Relevante Belege werden über semantische Suche ermittelt.
5. Der gefundene Kontext wird an das LLM zur Analyse übergeben.

## Vorteile

- Reduziertes Halluzinationsrisiko
- Nachvollziehbare Beleg‑Referenzen
- Verbesserte rechtliche Erklärbarkeit

## Technologien

- FAISS (Vektorsuche)
- MySQL (relationale Daten)
- Ollama (lokale LLM‑Inference)