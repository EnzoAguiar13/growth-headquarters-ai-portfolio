# Fotograma AI

> Plataforma própria de imagem e vídeo

## Resumo executivo

Produto em desenvolvimento para geração e edição de mídia por navegador, com execução em infraestrutura controlada.

## Problema que endereça

Viabilizar fluxos de criação de imagem e vídeo sem expor a operação interna de infraestrutura e modelos.

## Contexto de utilização

Uso em uma aplicação web com processamento de mídia em serviços próprios.

## Implementado

- Aplicação web autenticada.
- API, fila de jobs e processamento de mídia com FFmpeg.
- Estrutura de deploy com containers e worker de GPU sob demanda.
- Testes de integração e fluxos de navegador documentados.

## Tecnologias confirmadas

Python, FastAPI, Next.js, TypeScript, Docker, FFmpeg e infraestrutura de GPU sob demanda.

## Desafio técnico relevante

Projetar processamento pesado com isolamento entre aplicação, jobs e inferência, incluindo desligamento de recursos ociosos.

## Participação

Projeto autoral de Enzo Aguiar, com atuação no desenho técnico e no desenvolvimento do produto.

## Estado atual

Em desenvolvimento. Inferência real de imagem, geração de vídeo e edição facial autorizada continuam planejadas, não implementadas.

## Divulgação responsável

Esta página é uma apresentação de portfólio. Código-fonte, credenciais, dados reais, configurações operacionais e detalhes internos permanecem privados. Não há imagens ou demonstrastrações públicas nesta versão.

[← Voltar ao Project Showcase](../README.md)