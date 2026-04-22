# docs/filters/ — planning notes

## Goal
Document speed filter, observation gap splitter, stop splitter,
traffic jam filter. Deck will be used for presentations. Deck is a 
prototype which will partly need to be re-built on internal 
confidential data.

## Format
Quarto revealjs, one .qmd per filter in docs/filters/, rendered
as a single deck.

## Per-filter slide template (4 slides)
1. What/why + one-line API
2. Before map
3. After map
4. Params + gotchas

## Open decisions (resolve after reading the code)
- folium embed vs static matplotlib+contextily
- canonical trace vs tailored per filter
- manual render vs Makefile/GHA
- speaker notes yes/no

## First task
Read the four filter implementations + tests. Summarize inputs,
params, outputs, edge cases. Don't draft docs yet.
