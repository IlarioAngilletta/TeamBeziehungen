# TeamBeziehungen
Hier sollen mit einem dynamischen Graphen die Beziehungen zwischen verschiedenen Teams der DB Systel dargestellt werden.

Die datenstruktur sieht wie folgt aus:

* **Team**
  * Name
  * Description
  * Contacts
  * Unit
  * Portfoliosegment
  
* **Topic**
  * Name

* **Organisation**
  * Name
  * Type: Unit, Cluster, Portfoliosegment

* **Skill**
  * Name
  * Type: Unit, Cluster, Portfoliosegment

Jedes dieser Objekte bezeichnet einen Knoten im Graphen und über die Informationen in den teams werden die Kannten (=Beziehungen) zu den Strukturinformationen (Topic und Organisation) gebildet. Die Skills werden aktuell nicht implementiert, aber könnten den Link zum Kompetenzmarktplatz bilden.
