# npl_zullwil

XTF -> GPKG:

```
java -jar /Users/stefan/apps/ili2gpkg-4.4.1/ili2gpkg-4.4.1.jar --dbfile npl_zullwil_stroke.gpkg --nameByTopic --defaultSrsCode 2056 --strokeArcs --disableValidation --models SO_Nutzungsplanung_20171118 --doSchemaImport --import 089_NP_20201023/089_NP_20201023.xtf
```

```
java -jar /Users/stefan/apps/ili2gpkg-4.4.1/ili2gpkg-4.4.1.jar --dbfile npl_zullwil_arcs.gpkg --nameByTopic --defaultSrsCode 2056 --disableValidation --models SO_Nutzungsplanung_20171118 --doSchemaImport --import 089_NP_20201023/089_NP_20201023.xtf
```

In QGIS überlagernde Flächen mit Typ joinen, Lärmempfindlichkeitspolygone selektieren und als Shapefile abspeichern.

Check Geometries...
