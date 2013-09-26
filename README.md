senegalhistory-data
===================

The data in Senegalhistory are json files, you can always create other files in this folder. 
theses files are used by senegalhistory as a data source view 
https://github.com/senegalouvert/senegalhistory/tree/master/db/okfn

for exmple
royaumes.json example is a data source used by senegalhistory .it give the history of the kingdoms of senegal


{
  "name"  : "Royaumes du Senegal",
  "owner" : "tester",
  "title" : "Royaumes du Senegal",
  "licenses": [{
    "id": "cc-by-sa",
    "name": "Creative Commons Attribution ShareAlike",
    "url": "http://creativecommons.org/licenses/by-sa/3.0/"
  }],
  "resources" : [{
    "name": "default",
    "schema": {
      "fields": null
    },
    "records": [
      {
        "id" : "a880106e-ce43-4463-8884-bafe67270aa8",
        "title" : "Tekrour",
        "image" : "http://upload.wikimedia.org/wikipedia/commons/b/bf/Senegal-reine-du-walo.jpg",
        "description" :"Le Tekrour (ou Tekrur ou Takrur) était un petit État d'Afrique de l'ouest qui s'épanouit en même temps que l'empire du Ghana. Il se trouvait dans la vallée du fleuve Sénégal. Il vivait du commerce de l'or (exploité dans la région du Bambouk), du sel d'Awlil et des céréales du Sahel, ainsi que de la traite des Noirs. Le royaume se convertit à l'islam vers le VIIe siècle.La déformation française de Tekrour a donné :Toucouleur.Selon des sources portugaises, vers 1510, l’or du Tekrour alimente deux caravanes annuelles qui par le Fezzan amènent en Égypte le métal jaune « en grande quantité »",
        "source"   : "http://fr.wikipedia.org/wiki/Tekrour",
        "start" : "1510-01-01",
        "location" : {"type": "Point", "coordinates": [-16.47949 , 16.00358]},
        "license" : "GFDL"
      },
      ...
      ...
      ...
  }

senegalhistory  use the strength of timemapper https://github.com/okfn/timemapper  
to give an visualization tools and map like this .
