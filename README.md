# COMP3607 — Multi-Player Jeopardy Game

## Summary
Console-based Java (Maven) Jeopardy game supporting:
- Load questions from CSV, JSON or XML
- 1–4 players, turn-based play
- Process-mining CSV log with ISO timestamps
- Summary report (TXT + DOCX)
- JUnit tests and GitHub Actions CI

## Build
Requires Java 17 and Maven.

```bash
mvn clean package
# jar at target/jeopardy-game-1.0.0-jar-with-dependencies.jar
