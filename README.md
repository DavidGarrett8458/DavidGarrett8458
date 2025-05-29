# import the standard Django Model
# from built-in library
from django.db import models
 
# declare a new model with a name "GeeksModel"
class GeeksModel(models.Model):

    # fields of the model
    title = models.CharField(max_length = 200)
    description = models.TextField()

    # renames the instances of the model
    # with their title name
    def __str__(self):
        return self.title- 👋 Hi, I’m @DavidGarrett8458
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️Hi I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
DavidGarrett8458/DavidGarrett8458 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
---> Gmail Adresse full configuration 
# import the standard Django Model
# from built-in library
from django.db import models
 
# declare a new model with a name "GeeksModel"
class GeeksModel(models.Model):

    # fields of the model
    title = models.CharField(max_length = 200)
    description = models.TextField()

    # renames the instances of the model
    # with their title name
    def __str__(self):
        return self.title