# TeamBeziehungen
In diesem Projekt sollen mit einem dynamischen Graphen die Beziehungen zwischen verschiedenen Teams der DB Systel dargestellt werden.

Die darzustellenden Objekte sind:

* **Team**
  * Name
  * Description
  * (Contacts - not for deployment on a GitPage)
  * Unit
  * Portfoliosegment
  
* **Topic**
  * Name

* **Organisation**
  * Name
  * Type: Unit, Cluster, Portfoliosegment

* **Skill**
  * Name


Jedes dieser Objekte stellt einen Knoten im Graphen dar und 
über die Informationen in den Teams werden die Kannten (=Beziehungen) 
zu den Strukturinformationen (Topic und Organisation) gebildet. 

Teams, die eine oder mehrere Strukturen gemeinsam aufweisen, erhalten eine direkte Beziehung. Die Skills werden aktuell nicht implementiert, aber könnten den Link zum Kompetenzmarktplatz bilden.
