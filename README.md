# Analyses

## Download Data
Pairwise
    Groups 012345
        North musician
        North non-musician
        South musician
        South non-musician
Feature
    Groups 012345
        North musician
        North non-musician
        South musician
        South non-musician

## Distance matrices
Average partial distance matrix 30x30 (-missing)
Average feature distance matrix 30x30 (full)
Individual pairwise distance -> take average of group -> combine with all groups
Individual feature distance matrices
    average
    per user

## Correlation

1. Japanese partial vs Indian partial (check previous code)
2. Japanese feature distance vs indian feature
3. average feature vs average pairwise
4. individual feature vs individual pairwise (plot on multiple and on 1)
5. avg north pairwise vs avg south pairwise
6. avg musician pairwise vs avg non-musician pairwise

## PCA
PCA of all features

## Kappa scores
Feature agreement

# Data

## Similarity endpoint

https://api.music.keio.moe/experiments/world_music_workshop_similarity/export


## Rank endpoint

https://api.music.keio.moe/experiments/world_music_workshop_rank/export


## Evaluation endpoint


https://api.music.keio.moe/experiments/world_music_workshop_evaluation/export


## Bollywood endpoint

https://api.music.keio.moe/experiments/indian_music_evaluation/export

sudo service docker start