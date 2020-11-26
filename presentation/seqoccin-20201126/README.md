# Présentation SeqOccIN détection de variants 26 novembre 2020

## Sujet

Détection des variants bovin (15X CLR PacBio) ?

## Présentation

[Slides](https://docs.google.com/presentation/d/12eUGKtTEzH7sekN2NCyUO0hsS11pTZPQjac4GkF_-2E/edit#slide=id.p1)

## Point à aborder

 - Sensibilité et précision pour la détection de SNP chez l'homme
 - Sensibilité et précision pour la détection de SV chez l'homme
 - Comparaison du nombre de SNPs trouvé chez l'homme (HG002) et le bovin (Génisse2)
 - Comparaison du nombre de SVs trouvé chez l'homme (HG002) et le bovin (Génisse2)
 - Concordance des génotypes

## Compte-rendu

  - Est-ce que le 15x CLR ne contre-balance pas par rapport au 5x Illumina en ayant une couverture plus homogène ?
    - Attendu: diminution de sensibilité devrait principalement impacté les SNPs hétérozygote en ILL. CLR ?
      - Vérifier l'évolution des proportions de génotypes
      - Regarder la distribution de couverture des lectures sur le génome
  - Clipping et perte de couverture en CLR
    - du a une absence de la référence, à un problème de qualité ?
      - comparer les couvertures séquencées vs mappées sur d'autres SMRTCell
      - Tester d'aligner sur une autre référence (assemblage de l'individu) et observer si la différence est toujours là
