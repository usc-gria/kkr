# Informe de la ontología


## Estadísticas del grafo fuente

- Triples totales: **5889380**
- Clases observadas: **54**
- Propiedades observadas (sin rdf:type): **220**
- Triples en la ontología extraída: **832**

## Prefijos
```turtle
@prefix linkedmdb: <https://triplydb.com/Triply/linkedmdb/vocab/> .
@prefix foaf: <http://xmlns.com/foaf/0.1/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
```

## Clases

| Clase                                                              | Instancias |
|--------------------------------------------------------------------|-----------|
| `linkedmdb:Performance`                                            | 199771 |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | 162199 |
| `linkedmdb:Film`                                                   | 98816 |
| `foaf:Person`                                                      | 97858 |
| `linkedmdb:Actor`                                                  | 68205 |
| `linkedmdb:FilmCut`                                                | 45423 |
| `linkedmdb:Writer`                                                 | 23664 |
| `linkedmdb:Director`                                               | 21966 |
| `linkedmdb:Producer`                                               | 18408 |
| `linkedmdb:FilmCrewGig`                                            | 17237 |
| `linkedmdb:FilmCharacter`                                          | 16118 |
| `linkedmdb:FilmDistributorRelationship`                            | 15256 |
| `linkedmdb:MusicContributor`                                       | 6639 |
| `linkedmdb:FilmJob`                                                | 4048 |
| `linkedmdb:Editor`                                                 | 3843 |
| `linkedmdb:Cinematographer`                                        | 3819 |
| `linkedmdb:ProductionCompany`                                      | 1928 |
| `linkedmdb:FilmLocation`                                           | 1463 |
| `linkedmdb:FilmSubject`                                            | 1397 |
| `linkedmdb:PersonalFilmAppearance`                                 | 1127 |
| `linkedmdb:FilmStoryContributor`                                   | 872 |
| `linkedmdb:FilmFestival`                                           | 840 |
| `foaf:Agent`                                                       | 703 |
| `linkedmdb:FilmFestivalEvent`                                      | 685 |
| `linkedmdb:FilmGenre`                                              | 478 |
| `linkedmdb:FilmRegionalReleaseDate`                                | 418 |
| `linkedmdb:ArtDirector`                                            | 365 |
| `linkedmdb:CostumeDesigner`                                        | 365 |
| `linkedmdb:FilmCompany`                                            | 338 |
| `linkedmdb:FilmProductionDesigner`                                 | 293 |
| `linkedmdb:FilmSeries`                                             | 283 |
| `linkedmdb:FilmCritic`                                             | 275 |
| `linkedmdb:CastingDirector`                                        | 273 |
| `linkedmdb:Country`                                                | 247 |
| `linkedmdb:FilmAwardsCeremony`                                     | 207 |
| `linkedmdb:FilmSetDesigner`                                        | 206 |
| `linkedmdb:FilmDistributor`                                        | 169 |
| `linkedmdb:DubbingPerformance`                                     | 118 |
| `linkedmdb:MinorFilmGenre`                                         | 109 |
| `linkedmdb:ContentRating`                                          | 108 |
| `linkedmdb:FilmFormat`                                             | 96 |
| `linkedmdb:FilmFeaturedSong`                                       | 72 |
| `linkedmdb:FilmFestivalSponsor`                                    | 70 |
| `linkedmdb:ContentRatingSystem`                                    | 61 |
| `linkedmdb:FilmTheorist`                                           | 53 |
| `linkedmdb:FilmCollection`                                         | 38 |
| `linkedmdb:FilmCompanyRelationship`                                | 36 |
| `linkedmdb:FilmCrewMember`                                         | 25 |
| `linkedmdb:FilmScreeningVenue`                                     | 23 |
| `linkedmdb:FilmDistributionMedium`                                 | 18 |
| `linkedmdb:SpecialFilmPerformanceType`                             | 16 |
| `linkedmdb:FilmFestivalFocus`                                      | 13 |
| `linkedmdb:PersonalFilmAppearanceType`                             | 7 |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_run>` | 7 |

## Propiedades

| Propiedad                                                                           | Tipo             | Usos   | Dominio                                                            | Rango                                                              |
|-------------------------------------------------------------------------------------|------------------|--------|--------------------------------------------------------------------|--------------------------------------------------------------------|
| `rdfs:label`                                                                        | DatatypeProperty | 722050 | multiple                                                           | `xsd:string`                                                       |
| `foaf:page`                                                                         | Property         | 577112 | multiple                                                           | multiple                                                           |
| `linkedmdb:performance`                                                             | ObjectProperty   | 390322 | multiple                                                           | `linkedmdb:Performance`                                            |
| `linkedmdb:actor`                                                                   | ObjectProperty   | 284409 | `linkedmdb:Film`                                                   | multiple                                                           |
| `linkedmdb:performance_performanceid`                                               | DatatypeProperty | 199771 | `linkedmdb:Performance`                                            | `xsd:int`                                                          |
| `linkedmdb:performance_actor`                                                       | DatatypeProperty | 199455 | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `linkedmdb:performance_film`                                                        | DatatypeProperty | 199324 | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/link_target>`                  | Property         | 162199 | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | multople                                                           |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/link_type>`                    | DatatypeProperty | 162199 | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | `xsd:string`                                                       |
| `linkedmdb:linkid`                                                                  | DatatypeProperty | 162199 | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | `xsd:int`                                                          |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_run>`                  | ObjectProperty   | 162199 | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_run>` |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/link_source>`                  | ObjectProperty   | 162199 | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | —                                                                  |
| `linkedmdb:filmid`                                                                  | DatatypeProperty | 98816  | `linkedmdb:Film`                                                   | `xsd:int`                                                          |
| `dct:title`                                                                         | DatatypeProperty | 98812  | `linkedmdb:Film`                                                   | `xsd:string`                                                       |
| `foaf:made`                                                                         | ObjectProperty   | 72198  | multiple                                                           | `linkedmdb:Film`                                                   |
| `linkedmdb:director`                                                                | ObjectProperty   | 72198  | `linkedmdb:Film`                                                   | multiple                                                           |
| `dct:date`                                                                          | DatatypeProperty | 71736  | `linkedmdb:Film`                                                   | `xsd:string`                                                       |
| `linkedmdb:initial_release_date`                                                    | DatatypeProperty | 71736  | `linkedmdb:Film`                                                   | `xsd:string`                                                       |
| `linkedmdb:actor_actorid`                                                           | DatatypeProperty | 68205  | multiple                                                           | `xsd:int`                                                          |
| `linkedmdb:actor_name`                                                              | DatatypeProperty | 68202  | multiple                                                           | `xsd:string`                                                       |
| `linkedmdb:runtime`                                                                 | DatatypeProperty | 65665  | multiple                                                           | `xsd:string`                                                       |
| `owl:sameAs`                                                                        | Property         | 63162  | multiple                                                           | multiple                                                           |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_score>`                | DatatypeProperty | 55599  | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/interlink>`   | `xsd:string`                                                       |
| `linkedmdb:producer`                                                                | ObjectProperty   | 51829  | `linkedmdb:Film`                                                   | `linkedmdb:Producer`                                               |
| `linkedmdb:writer`                                                                  | ObjectProperty   | 48616  | `linkedmdb:Film`                                                   | `linkedmdb:Writer`                                                 |
| `linkedmdb:film_cut_film_cutid`                                                     | DatatypeProperty | 45423  | `linkedmdb:FilmCut`                                                | `xsd:int`                                                          |
| `linkedmdb:genre`                                                                   | ObjectProperty   | 41061  | `linkedmdb:Film`                                                   | `linkedmdb:FilmGenre`                                              |
| `foaf:based_near>`                                                                  | Property         | 33745  | `linkedmdb:Film`                                                   | —                                                                  |
| `linkedmdb:country`                                                                 | ObjectProperty   | 33745  | `linkedmdb:Film`                                                   | `linkedmdb:Country`                                                |
| `linkedmdb:music_contributor`                                                       | ObjectProperty   | 31466  | `linkedmdb:Film`                                                   | `linkedmdb:MusicContributor`                                       |
| `<http://dbpedia.org/property/hasPhotoCollection>`                                  | Property         | 30354  | —                                                                  | —                                                                  |
| `linkedmdb:language`                                                                | Property         | 28253  | `linkedmdb:Film`                                                   | —                                                                  |
| `linkedmdb:writer_writerid`                                                         | DatatypeProperty | 23664  | `linkedmdb:Writer`                                                 | `xsd:int`                                                          |
| `linkedmdb:writer_name`                                                             | DatatypeProperty | 23664  | `linkedmdb:Writer`                                                 | `xsd:string`                                                       |
| `linkedmdb:director_directorid`                                                     | DatatypeProperty | 21966  | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:director_name`                                                           | DatatypeProperty | 21966  | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:film_cut`                                                                | ObjectProperty   | 20248  | `linkedmdb:Film`                                                   | `linkedmdb:FilmCut`                                                |
| `linkedmdb:producer_producerid`                                                     | DatatypeProperty | 18408  | `linkedmdb:Producer`                                               | `xsd:int`                                                          |
| `linkedmdb:producer_name`                                                           | DatatypeProperty | 18408  | `linkedmdb:Producer`                                               | `xsd:string`                                                       |
| `linkedmdb:film_character`                                                          | ObjectProperty   | 17822  | `linkedmdb:Performance`                                            | `linkedmdb:FilmCharacter`                                          |
| `linkedmdb:film_crew_gig_film_crew_gigid`                                           | DatatypeProperty | 17237  | `linkedmdb:FilmCrewGig`                                            | `xsd:int`                                                          |
| `linkedmdb:film_crew_gig_id`                                                        | DatatypeProperty | 17237  | `linkedmdb:FilmCrewGig`                                            | `xsd:string`                                                       |
| `linkedmdb:film_crew_role`                                                          | DatatypeProperty | 17171  | `linkedmdb:FilmCrewGig`                                            | `xsd:string`                                                       |
| `linkedmdb:film_crew_gig_film`                                                      | ObjectProperty   | 17081  | `linkedmdb:FilmCrewGig`                                            | `linkedmdb:Film`                                                   |
| `linkedmdb:film_crew_gig_film_job`                                                  | ObjectProperty   | 17074  | `linkedmdb:FilmCrewGig`                                            | `linkedmdb:FilmJob`                                                |
| `linkedmdb:film_character_film_characterid`                                         | DatatypeProperty | 16118  | `linkedmdb:FilmCharacter`                                          | `xsd:int`                                                          |
| `linkedmdb:film_character_name`                                                     | DatatypeProperty | 16116  | `linkedmdb:FilmCharacter`                                          | `xsd:string`                                                       |
| `linkedmdb:film_film_distributor_relationship_freebase_url`                         | Property         | 15256  | `linkedmdb:FilmDistributorRelationship`                            | —                                                                  |
| `linkedmdb:film_film_distributor_relationship_film_film_distributor_relationshipid` | DatatypeProperty | 15256  | `linkedmdb:FilmDistributorRelationship`                            | `xsd:int`                                                          |
| `linkedmdb:film_film_distributor_relationship_distributor`                          | DatatypeProperty | 15253  | `linkedmdb:FilmDistributorRelationship`                            | `xsd:string`                                                       |
| `linkedmdb:film_distributor`                                                        | ObjectProperty   | 15248  | `linkedmdb:FilmDistributorRelationship`                            | `linkedmdb:FilmDistributor`                                        |
| `linkedmdb:film_of_distributor`                                                     | ObjectProperty   | 15220  | `linkedmdb:FilmDistributorRelationship`                            | `linkedmdb:Film`                                                   |
| `linkedmdb:performance_character`                                                   | DatatypeProperty | 13393  | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `rdfs:SeeAlso`                                                                      | Property         | 12990  | `linkedmdb:Writer`                                                 | —                                                                  |
| `linkedmdb:editor`                                                                  | ObjectProperty   | 12676  | `linkedmdb:Film`                                                   | (union)                                                            |
| `linkedmdb:production_company`                                                      | ObjectProperty   | 10920  | `linkedmdb:Film`                                                   | `linkedmdb:ProductionCompany`                                      |
| `linkedmdb:cinematographer`                                                         | ObjectProperty   | 7127   | `linkedmdb:Film`                                                   | (union)                                                            |
| `<http://www.w3.org/2004/02/skos/core#subject>`                                     | ObjectProperty   | 6661   | `linkedmdb:Film`                                                   | `linkedmdb:FilmSubject`                                            |
| `linkedmdb:music_contributor_music_contributorid`                                   | DatatypeProperty | 6639   | `linkedmdb:MusicContributor`                                       | `xsd:int`                                                          |
| `linkedmdb:music_contributor_name`                                                  | DatatypeProperty | 6639   | `linkedmdb:MusicContributor`                                       | `xsd:string`                                                       |
| `linkedmdb:film_subject`                                                            | ObjectProperty   | 6412   | `linkedmdb:Film`                                                   | `linkedmdb:FilmSubject`                                            |
| `linkedmdb:performance_special_performance_type`                                    | Property         | 5986   | `linkedmdb:Performance`                                            | —                                                                  |
| `linkedmdb:sequel`                                                                  | ObjectProperty   | 5206   | `linkedmdb:Film`                                                   | `linkedmdb:Film`                                                   |
| `linkedmdb:featured_film_location`                                                  | ObjectProperty   | 4870   | `linkedmdb:Film`                                                   | `linkedmdb:FilmLocation`                                           |
| `linkedmdb:film_job_name`                                                           | DatatypeProperty | 4048   | `linkedmdb:FilmJob`                                                | `xsd:string`                                                       |
| `linkedmdb:film_job_film_jobid`                                                     | DatatypeProperty | 4048   | `linkedmdb:FilmJob`                                                | `xsd:int`                                                          |
| `linkedmdb:prequel`                                                                 | ObjectProperty   | 3989   | `linkedmdb:Film`                                                   | `linkedmdb:Film`                                                   |
| `linkedmdb:editor_name`                                                             | DatatypeProperty | 3843   | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:editor_editorid`                                                         | DatatypeProperty | 3843   | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:cinematographer_cinematographerid`                                       | DatatypeProperty | 3819   | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:cinematographer_name`                                                    | DatatypeProperty | 3819   | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:performance_part`                                                        | DatatypeProperty | 2717   | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `linkedmdb:film_art_director`                                                       | ObjectProperty   | 2625   | `linkedmdb:Film`                                                   | `linkedmdb:ArtDirector`                                            |
| `linkedmdb:production_company_production_companyid`                                 | DatatypeProperty | 1928   | `linkedmdb:ProductionCompany`                                      | `xsd:int`                                                          |
| `linkedmdb:production_company_name`                                                 | DatatypeProperty | 1926   | `linkedmdb:ProductionCompany`                                      | `xsd:string`                                                       |
| `linkedmdb:story_contributor`                                                       | ObjectProperty   | 1621   | `linkedmdb:Film`                                                   | `linkedmdb:FilmStoryContributor`                                   |
| `linkedmdb:film_location_film_locationid`                                           | DatatypeProperty | 1463   | `linkedmdb:FilmLocation`                                           | `xsd:int`                                                          |
| `linkedmdb:film_location_name`                                                      | DatatypeProperty | 1463   | `linkedmdb:FilmLocation`                                           | `xsd:string`                                                       |
| `linkedmdb:film_format`                                                             | ObjectProperty   | 1427   | `linkedmdb:Film`                                                   | `linkedmdb:FilmFormat`                                             |
| `linkedmdb:film_subject_film_subjectid`                                             | DatatypeProperty | 1397   | `linkedmdb:FilmSubject`                                            | `xsd:int`                                                          |
| `linkedmdb:film_subject_name`                                                       | DatatypeProperty | 1397   | `linkedmdb:FilmSubject`                                            | `xsd:string`                                                       |
| `linkedmdb:film_story_contributor`                                                  | ObjectProperty   | 1262   | `linkedmdb:Film`                                                   | `linkedmdb:FilmStoryContributor`                                   |
| `linkedmdb:personal_film_appearance_personal_film_appearanceid`                     | DatatypeProperty | 1127   | `linkedmdb:PersonalFilmAppearance`                                 | `xsd:int`                                                          |
| `linkedmdb:personal_film_appearance_person`                                         | DatatypeProperty | 1127   | `linkedmdb:PersonalFilmAppearance`                                 | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance`                                                | ObjectProperty   | 1118   | `linkedmdb:Film`                                                   | `linkedmdb:PersonalFilmAppearance`                                 |
| `linkedmdb:executive_producer`                                                      | ObjectProperty   | 954    | `linkedmdb:Film`                                                   | `linkedmdb:Producer`                                               |
| `linkedmdb:film_story_contributor_name`                                             | DatatypeProperty | 872    | `linkedmdb:FilmStoryContributor`                                   | `xsd:string`                                                       |
| `linkedmdb:film_story_contributor_film_story_contributorid`                         | DatatypeProperty | 872    | `linkedmdb:FilmStoryContributor`                                   | `xsd:int`                                                          |
| `linkedmdb:film_festival_name`                                                      | DatatypeProperty | 840    | `linkedmdb:FilmFestival`                                           | `xsd:string`                                                       |
| `linkedmdb:film_festival_film_festivalid`                                           | DatatypeProperty | 840    | `linkedmdb:FilmFestival`                                           | `xsd:int`                                                          |
| `linkedmdb:relatedBook`                                                             | Property         | 700    | `linkedmdb:Film`                                                   | —                                                                  |
| `linkedmdb:film_festival_event_film_festival_event_id`                              | DatatypeProperty | 685    | `linkedmdb:FilmFestivalEvent`                                      | `xsd:int`                                                          |
| `linkedmdb:film_festival_event_freebase_url`                                        | DatatypeProperty | 685    | `linkedmdb:FilmFestivalEvent`                                      | `xsd:string`                                                       |
| `linkedmdb:film_festival_event_name`                                                | DatatypeProperty | 621    | `linkedmdb:FilmFestivalEvent`                                      | `xsd:string`                                                       |
| `linkedmdb:film_production_designer`                                                | ObjectProperty   | 581    | `linkedmdb:Film`                                                   | `linkedmdb:FilmProductionDesigner`                                 |
| `linkedmdb:film_casting_director`                                                   | ObjectProperty   | 542    | `linkedmdb:Film`                                                   | `linkedmdb:CastingDirector`                                        |
| `linkedmdb:film_festival_event`                                                     | ObjectProperty   | 535    | `linkedmdb:FilmFestival`                                           | `linkedmdb:FilmFestivalEvent`                                      |
| `linkedmdb:location`                                                                | ObjectProperty   | 533    | `linkedmdb:Film`                                                   | `linkedmdb:FilmLocation`                                           |
| `linkedmdb:film_collection`                                                         | ObjectProperty   | 485    | `linkedmdb:Film`                                                   | `linkedmdb:FilmCollection`                                         |
| `linkedmdb:film_genre_film_genreid`                                                 | DatatypeProperty | 478    | `linkedmdb:FilmGenre`                                              | `xsd:int`                                                          |
| `linkedmdb:film_genre_name`                                                         | DatatypeProperty | 478    | `linkedmdb:FilmGenre`                                              | `xsd:string`                                                       |
| `linkedmdb:film_set_designer`                                                       | ObjectProperty   | 461    | `linkedmdb:Film`                                                   | `linkedmdb:FilmSetDesigner`                                        |
| `linkedmdb:film_regional_release_date_film_regional_release_id`                     | DatatypeProperty | 418    | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:int`                                                          |
| `linkedmdb:film_regional_release_date_freebase_url`                                 | Property         | 418    | `linkedmdb:FilmRegionalReleaseDate`                                | —                                                                  |
| `linkedmdb:film_regional_release_date_release_date`                                 | DatatypeProperty | 415    | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:string`                                                       |
| `linkedmdb:film_regional_release_date`                                              | ObjectProperty   | 413    | `linkedmdb:Film`                                                   | `linkedmdb:FilmRegionalReleaseDate`                                |
| `linkedmdb:film_regional_release_date_film_release_region`                          | DatatypeProperty | 384    | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:string`                                                       |
| `linkedmdb:film_cut_note`                                                           | DatatypeProperty | 383    | `linkedmdb:FilmCut`                                                | `xsd:string`                                                       |
| `linkedmdb:film_costume_designer_film_costume_designerid`                           | DatatypeProperty | 365    | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:film_art_director_name`                                                  | DatatypeProperty | 365    | `linkedmdb:ArtDirector`                                            | `xsd:string`                                                       |
| `linkedmdb:film_art_director_id`                                                    | DatatypeProperty | 365    | `linkedmdb:ArtDirector`                                            | `xsd:int`                                                          |
| `linkedmdb:film_costume_designer_name`                                              | DatatypeProperty | 365    | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:film_company_name`                                                       | DatatypeProperty | 338    | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:film_company_film_companyid`                                             | DatatypeProperty | 338    | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:film_production_designer_freebase_url`                                   | Property         | 293    | `linkedmdb:FilmProductionDesigner`                                 | —                                                                  |
| `linkedmdb:film_production_designer_name`                                           | DatatypeProperty | 293    | `linkedmdb:FilmProductionDesigner`                                 | `xsd:string`                                                       |
| `linkedmdb:film_production_designer_film_production_designer_id`                    | DatatypeProperty | 293    | `linkedmdb:FilmProductionDesigner`                                 | `xsd:int`                                                          |
| `linkedmdb:film_series_film_seriesid`                                               | DatatypeProperty | 283    | `linkedmdb:FilmSeries`                                             | `xsd:int`                                                          |
| `linkedmdb:film_series_name`                                                        | DatatypeProperty | 283    | `linkedmdb:FilmSeries`                                             | `xsd:string`                                                       |
| `linkedmdb:film_critic_film_criticid`                                               | DatatypeProperty | 275    | `linkedmdb:FilmCritic`                                             | `xsd:int`                                                          |
| `linkedmdb:film_critic_name`                                                        | DatatypeProperty | 275    | `linkedmdb:FilmCritic`                                             | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance_type_of_appearance`                             | DatatypeProperty | 275    | `linkedmdb:PersonalFilmAppearance`                                 | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance_type`                                           | ObjectProperty   | 275    | `linkedmdb:PersonalFilmAppearance`                                 | `linkedmdb:PersonalFilmAppearanceType`                             |
| `linkedmdb:film_casting_director_freebase_url`                                      | Property         | 273    | `linkedmdb:CastingDirector`                                        | —                                                                  |
| `linkedmdb:film_casting_director_film_casting_director_id`                          | DatatypeProperty | 273    | `linkedmdb:CastingDirector`                                        | `xsd:int`                                                          |
| `linkedmdb:film_casting_director_name`                                              | DatatypeProperty | 272    | `linkedmdb:CastingDirector`                                        | `xsd:string`                                                       |
| `linkedmdb:country_population`                                                      | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_iso_alpha3`                                                      | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_id`                                                              | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:int`                                                          |
| `linkedmdb:country_name`                                                            | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_iso_numeric`                                                     | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_areaInSqKm`                                                      | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:double`                                                       |
| `linkedmdb:country_fips_code`                                                       | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_continent`                                                       | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_iso_alpha2`                                                      | DatatypeProperty | 247    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_currency`                                                        | DatatypeProperty | 246    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_languages`                                                       | DatatypeProperty | 244    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:country_capital`                                                         | DatatypeProperty | 242    | `linkedmdb:Country`                                                | `xsd:string`                                                       |
| `linkedmdb:film_series`                                                             | ObjectProperty   | 233    | `linkedmdb:Film`                                                   | `linkedmdb:FilmSeries`                                             |
| `linkedmdb:rating`                                                                  | ObjectProperty   | 209    | `linkedmdb:Film`                                                   | `linkedmdb:ContentRating`                                          |
| `linkedmdb:film_awards_ceremony_name`                                               | DatatypeProperty | 207    | `linkedmdb:FilmAwardsCeremony`                                     | `xsd:string`                                                       |
| `linkedmdb:film_awards_ceremony_id`                                                 | DatatypeProperty | 207    | `linkedmdb:FilmAwardsCeremony`                                     | `xsd:string`                                                       |
| `linkedmdb:film_awards_ceremony_film_awards_ceremonyid`                             | DatatypeProperty | 207    | `linkedmdb:FilmAwardsCeremony`                                     | `xsd:int`                                                          |
| `linkedmdb:film_set_designer_freebase_url`                                          | Property         | 206    | `linkedmdb:FilmSetDesigner`                                        | —                                                                  |
| `linkedmdb:film_set_designer_name`                                                  | DatatypeProperty | 206    | `linkedmdb:FilmSetDesigner`                                        | `xsd:string`                                                       |
| `linkedmdb:film_set_designer_film_set_designer_id`                                  | DatatypeProperty | 206    | `linkedmdb:FilmSetDesigner`                                        | `xsd:int`                                                          |
| `linkedmdb:film_distributor_name`                                                   | DatatypeProperty | 169    | `linkedmdb:FilmDistributor`                                        | `xsd:string`                                                       |
| `linkedmdb:film_distributor_film_distributorid`                                     | DatatypeProperty | 169    | `linkedmdb:FilmDistributor`                                        | `xsd:int`                                                          |
| `linkedmdb:film_distributor_freebase_url`                                           | Property         | 169    | `linkedmdb:FilmDistributor`                                        | —                                                                  |
| `linkedmdb:performance_note`                                                        | DatatypeProperty | 153    | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `linkedmdb:film_film_distributor_relationship_year`                                 | DatatypeProperty | 144    | `linkedmdb:FilmDistributorRelationship`                            | `xsd:string`                                                       |
| `linkedmdb:film_regional_release_date_film_release_distribution_medium`             | DatatypeProperty | 144    | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:string`                                                       |
| `linkedmdb:dubbing_performance_dubbing_performanceid`                               | DatatypeProperty | 118    | `linkedmdb:DubbingPerformance`                                     | `xsd:int`                                                          |
| `linkedmdb:dubbing_performance_film`                                                | DatatypeProperty | 117    | `linkedmdb:DubbingPerformance`                                     | `xsd:string`                                                       |
| `linkedmdb:dubbing_performance`                                                     | ObjectProperty   | 115    | `linkedmdb:Film`                                                   | `linkedmdb:DubbingPerformance`                                     |
| `linkedmdb:dubbing_performance_actor`                                               | DatatypeProperty | 114    | `linkedmdb:DubbingPerformance`                                     | `xsd:string`                                                       |
| `linkedmdb:minor_film_genre_minor_film_genreid`                                     | DatatypeProperty | 109    | `linkedmdb:MinorFilmGenre`                                         | `xsd:int`                                                          |
| `linkedmdb:minor_film_genre_name`                                                   | DatatypeProperty | 109    | `linkedmdb:MinorFilmGenre`                                         | `xsd:string`                                                       |
| `linkedmdb:type_of_film_cut`                                                        | DatatypeProperty | 108    | `linkedmdb:FilmCut`                                                | `xsd:string`                                                       |
| `linkedmdb:content_rating_content_ratingid`                                         | DatatypeProperty | 108    | `linkedmdb:ContentRating`                                          | `xsd:int`                                                          |
| `linkedmdb:content_rating_name`                                                     | DatatypeProperty | 108    | `linkedmdb:ContentRating`                                          | `xsd:string`                                                       |
| `linkedmdb:content_rating_country`                                                  | DatatypeProperty | 99     | `linkedmdb:ContentRating`                                          | `xsd:string`                                                       |
| `linkedmdb:content_rating_system`                                                   | ObjectProperty   | 99     | `linkedmdb:ContentRating`                                          | `linkedmdb:ContentRatingSystem`                                    |
| `linkedmdb:content_rating_film_rating_system`                                       | DatatypeProperty | 99     | `linkedmdb:ContentRating`                                          | `xsd:string`                                                       |
| `linkedmdb:film_format_name`                                                        | DatatypeProperty | 96     | `linkedmdb:FilmFormat`                                             | `xsd:string`                                                       |
| `linkedmdb:film_distribution_medium`                                                | ObjectProperty   | 96     | `linkedmdb:FilmDistributorRelationship`                            | `linkedmdb:FilmDistributionMedium`                                 |
| `linkedmdb:film_format_film_formatid`                                               | DatatypeProperty | 96     | `linkedmdb:FilmFormat`                                             | `xsd:int`                                                          |
| `linkedmdb:film_film_distributor_relationship_film_distribution_medium`             | DatatypeProperty | 95     | `linkedmdb:FilmDistributorRelationship`                            | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance_film`                                           | DatatypeProperty | 93     | `linkedmdb:PersonalFilmAppearance`                                 | `xsd:string`                                                       |
| `linkedmdb:film_film_distributor_relationship_region`                               | DatatypeProperty | 79     | `linkedmdb:FilmDistributorRelationship`                            | `xsd:string`                                                       |
| `linkedmdb:film_featured_song_name`                                                 | DatatypeProperty | 72     | `linkedmdb:FilmFeaturedSong`                                       | `xsd:string`                                                       |
| `linkedmdb:film_featured_song_film_featured_song_id`                                | DatatypeProperty | 72     | `linkedmdb:FilmFeaturedSong`                                       | `xsd:int`                                                          |
| `linkedmdb:film_featured_song_freebase_url`                                         | Property         | 72     | `linkedmdb:FilmFeaturedSong`                                       | —                                                                  |
| `linkedmdb:film_featured_song`                                                      | ObjectProperty   | 71     | `linkedmdb:Film`                                                   | `linkedmdb:FilmFeaturedSong`                                       |
| `linkedmdb:film_festival_sponsor_name`                                              | DatatypeProperty | 70     | `linkedmdb:FilmFestivalSponsor`                                    | `xsd:string`                                                       |
| `linkedmdb:film_festival_sponsor_freebase_url`                                      | Property         | 70     | `linkedmdb:FilmFestivalSponsor`                                    | —                                                                  |
| `linkedmdb:film_festival_sponsor_film_festival_sponsor_id`                          | DatatypeProperty | 70     | `linkedmdb:FilmFestivalSponsor`                                    | `xsd:int`                                                          |
| `linkedmdb:content_rating_minimum_unaccompanied_age`                                | DatatypeProperty | 62     | `linkedmdb:ContentRating`                                          | `xsd:int`                                                          |
| `linkedmdb:content_rating_system_content_rating_systemid`                           | DatatypeProperty | 61     | `linkedmdb:ContentRatingSystem`                                    | `xsd:int`                                                          |
| `linkedmdb:content_rating_system_name`                                              | DatatypeProperty | 61     | `linkedmdb:ContentRatingSystem`                                    | `xsd:string`                                                       |
| `linkedmdb:film_theorist_name`                                                      | DatatypeProperty | 53     | `linkedmdb:FilmTheorist`                                           | `xsd:string`                                                       |
| `linkedmdb:film_theorist_film_theoristid`                                           | DatatypeProperty | 53     | `linkedmdb:FilmTheorist`                                           | `xsd:int`                                                          |
| `linkedmdb:film_featured_song_performed_by`                                         | DatatypeProperty | 48     | `linkedmdb:FilmFeaturedSong`                                       | `xsd:string`                                                       |
| `linkedmdb:content_rating_system_jurisdiction`                                      | DatatypeProperty | 45     | `linkedmdb:ContentRatingSystem`                                    | `xsd:string`                                                       |
| `linkedmdb:film_collection_film_collectionid`                                       | DatatypeProperty | 38     | `linkedmdb:FilmCollection`                                         | `xsd:int`                                                          |
| `linkedmdb:film_collection_name`                                                    | DatatypeProperty | 38     | `linkedmdb:FilmCollection`                                         | `xsd:string`                                                       |
| `linkedmdb:film_film_company_relationship`                                          | ObjectProperty   | 36     | `linkedmdb:Film`                                                   | `linkedmdb:FilmCompanyRelationship`                                |
| `linkedmdb:film_film_company_relationship_freebase_url`                             | Property         | 36     | `linkedmdb:FilmCompanyRelationship`                                | —                                                                  |
| `linkedmdb:film_film_company_relationship_film_film_company_relationshipid`         | DatatypeProperty | 36     | `linkedmdb:FilmCompanyRelationship`                                | `xsd:int`                                                          |
| `linkedmdb:film_release_region`                                                     | DatatypeProperty | 35     | `linkedmdb:FilmCut`                                                | `xsd:string`                                                       |
| `linkedmdb:dubbing_performance_language`                                            | DatatypeProperty | 31     | `linkedmdb:DubbingPerformance`                                     | `xsd:string`                                                       |
| `linkedmdb:film_regional_release_date_film_regional_debut_venue`                    | DatatypeProperty | 30     | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:string`                                                       |
| `linkedmdb:costume_designer`                                                        | ObjectProperty   | 26     | `linkedmdb:Film`                                                   | (union)                                                            |
| `linkedmdb:film_crewmember_film_crewmemberid`                                       | DatatypeProperty | 25     | (union)                                                            | `xsd:int`                                                          |
| `linkedmdb:crew_gig_film`                                                           | DatatypeProperty | 25     | `linkedmdb:FilmCrewGig`                                            | `xsd:string`                                                       |
| `linkedmdb:film_crewmember_name`                                                    | DatatypeProperty | 25     | (union)                                                            | `xsd:string`                                                       |
| `linkedmdb:crewmember`                                                              | DatatypeProperty | 25     | `linkedmdb:FilmCrewGig`                                            | `xsd:string`                                                       |
| `linkedmdb:film_crewmember`                                                         | ObjectProperty   | 24     | `linkedmdb:FilmCrewGig`                                            | (union)                                                            |
| `linkedmdb:dubbing_performance_character`                                           | DatatypeProperty | 23     | `linkedmdb:DubbingPerformance`                                     | `xsd:string`                                                       |
| `linkedmdb:film_screening_venue_freebase_url`                                       | Property         | 23     | `linkedmdb:FilmScreeningVenue`                                     | —                                                                  |
| `linkedmdb:film_screening_venue_film_screening_venue_id`                            | DatatypeProperty | 23     | `linkedmdb:FilmScreeningVenue`                                     | `xsd:int`                                                          |
| `linkedmdb:film_screening_venue_name`                                               | DatatypeProperty | 23     | `linkedmdb:FilmScreeningVenue`                                     | `xsd:string`                                                       |
| `linkedmdb:film_distribution_medium_film_distribution_mediumid`                     | DatatypeProperty | 18     | `linkedmdb:FilmDistributionMedium`                                 | `xsd:int`                                                          |
| `linkedmdb:film_distribution_medium_name`                                           | DatatypeProperty | 18     | `linkedmdb:FilmDistributionMedium`                                 | `xsd:string`                                                       |
| `linkedmdb:special_film_performance_type_name`                                      | DatatypeProperty | 16     | `linkedmdb:SpecialFilmPerformanceType`                             | `xsd:string`                                                       |
| `linkedmdb:special_film_performance_type_special_film_performance_typeid`           | DatatypeProperty | 16     | `linkedmdb:SpecialFilmPerformanceType`                             | `xsd:int`                                                          |
| `linkedmdb:film_film_distributor_relationship_film_cut`                             | DatatypeProperty | 13     | `linkedmdb:FilmDistributorRelationship`                            | `xsd:string`                                                       |
| `linkedmdb:film_festival_focus_name`                                                | DatatypeProperty | 13     | `linkedmdb:FilmFestivalFocus`                                      | `xsd:string`                                                       |
| `linkedmdb:film_festival_focus_freebase_url`                                        | Property         | 13     | `linkedmdb:FilmFestivalFocus`                                      | —                                                                  |
| `linkedmdb:film_festival_focus_film_festival_focus_id`                              | DatatypeProperty | 13     | `linkedmdb:FilmFestivalFocus`                                      | `xsd:int`                                                          |
| `linkedmdb:film_film_company_relationship_role_service`                             | DatatypeProperty | 13     | `linkedmdb:FilmCompanyRelationship`                                | `xsd:string`                                                       |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_method>`               | DatatypeProperty | 7      | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_run>` | `xsd:string`                                                       |
| `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_date>`                 | DatatypeProperty | 7      | `<https://triplydb.com/Triply/linkedmdb/id/oddlinker/linkage_run>` | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance_type_name`                                      | DatatypeProperty | 7      | `linkedmdb:PersonalFilmAppearanceType`                             | `xsd:string`                                                       |
| `linkedmdb:personal_film_appearance_type_personal_film_appearance_typeid`           | DatatypeProperty | 7      | `linkedmdb:PersonalFilmAppearanceType`                             | `xsd:int`                                                          |
| `linkedmdb:film_festival_event_opening_date`                                        | DatatypeProperty | 6      | `linkedmdb:FilmFestivalEvent`                                      | `xsd:string`                                                       |
| `linkedmdb:performance_name`                                                        | DatatypeProperty | 4      | `linkedmdb:Performance`                                            | `xsd:string`                                                       |
| `linkedmdb:film_festival_event_closing_date`                                        | DatatypeProperty | 1      | `linkedmdb:FilmFestivalEvent`                                      | `xsd:string`                                                       |
| `linkedmdb:film_company`                                                            | ObjectProperty   | 1      | `linkedmdb:FilmCompanyRelationship`                                | (union)                                                            |
| `linkedmdb:film_regional_release_date_name`                                         | DatatypeProperty | 1      | `linkedmdb:FilmRegionalReleaseDate`                                | `xsd:string`                                                       |

## Subclases inferidas

| Subclase                    | Superclase    | 
|-----------------------------|---------------|
| `linkedmdb:Actor`           | `foaf:Person` | 
| `linkedmdb:Director`        | `foaf:Person` | 
| `linkedmdb:Editor`          | `foaf:Person` | 
| `linkedmdb:Cinematographer` | `foaf:Person` |
| `linkedmdb:CostumeDesigner` | `foaf:Agent`  |
| `linkedmdb:FilmCompany`     | `foaf:Agent`  | 
| `linkedmdb:FilmCrewMember`  | `foaf:Person` | 

## Consulta SPARQL para obtener el dominio y el rango de una propiedad

```sparql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>

SELECT DISTINCT ?dominio ?rango WHERE {
    ?s <MI_PROPIEDAD> ?o .
    ?s rdf:type ?dominio .
    ?o rdf:type ?rango .
    
}
```

Por ejemplo, para la propiedad `linkedmdb:film_company` sería:
```sparql
PREFIX rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX linkedmdb: <https://triplydb.com/Triply/linkedmdb/vocab/>

SELECT DISTINCT ?dominio ?rango WHERE {
    ?s linkedmdb:film_company ?o .
    ?s rdf:type ?dominio .
    ?o rdf:type ?rango .
    
}
```

> [!WARNING]
> Las consultas de arriba solo funcionarán para las Object Properties, las Datatype Properties no tienen explicitamente definido el rango, por lo que lo mejor será comentar ese Triple Pattern.

