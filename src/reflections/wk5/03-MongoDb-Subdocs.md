# MongoDB Subdocs

## In simple terms what is a sub-document?

* Subdocuments are documents that are nested in other documents. Typically a Schema nested in another Schema. Mongo DB will automatically do it for you if you nest a object in another object.

## When might you use a sub-document?

* You would want to use a subdocument when adding a section of data to an object that already exists. ex: adding an array of moves a certain character that already exists.

## How do you add to a collection of sub-documents? What about editing them?

* To add to a collection of sub docs you would access that subdoc and add in the objects/data you wanted in the right locations then save. ex: const ryu = new Character({name:'Ryu'}) const ryu.specials = [{ special 1, special2, special3}], after adding in the data you run save. const doc = await ryu.save()

daily challenge link - https://talanweeks.github.io/space-relations/ 