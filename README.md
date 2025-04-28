# Lagerassistent (Warehouse Assistant)

Ein Python-basiertes Lagerverwaltungssystem, entwickelt als Universitätsprojekt.

## Voraussetzungen

- Python 3.11 oder höher
- `uv` als Python Paketmanager (empfohlen)

## Installation

1. Repository klonen:
```bash
git clone https://github.com/[username]/Gruppe2-Lagerassistent.git
cd Gruppe2-Lagerassistent
```

2. Virtuelle Umgebung erstellen und Abhängigkeiten installieren:

Mit uv (empfohlen):
```bash
uv venv
source .venv/bin/activate  # Unter Unix/macOS
# oder
.venv\Scripts\activate     # Unter Windows
uv sync
```

Alternativ mit pip:
```bash
python -m venv .venv
source .venv/bin/activate  # Unter Unix/macOS
# oder
.venv\Scripts\activate     # Unter Windows
pip install openai python-dotenv gradio openai-agents
```

## Projektstruktur

```
Gruppe2-Lagerassistent/
├── main.py              # Hauptanwendungsdatei
├── pyproject.toml       # Projektabhängigkeiten und Konfiguration
├── README.md           # Diese Datei
└── .venv/              # Virtuelle Umgebung (wird bei Installation erstellt)
```

## Abhängigkeiten

Das Projekt verwendet folgende Hauptabhängigkeiten:
- openai
- python-dotenv
- gradio
- openai-agents

Die vollständige Liste der Abhängigkeiten finden Sie in der `pyproject.toml` Datei.

## Entwicklung

Um das Projekt zu entwickeln:

1. Stellen Sie sicher, dass die virtuelle Umgebung aktiviert ist
2. Führen Sie die Anwendung aus:
```bash
python main.py
```

## Lizenz

[Lizenzinformationen hinzufügen]