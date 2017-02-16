# timeline-datalet
A Timeline Datalet for time based data visualizzation in DEEP
Before using this datalet on SPOD, you must add this lines to "\Datalet-Ecosystem-Provider\deep\datalets.xml":
```xml
        <!--Timeline-->
        <component>
            <name>timeline-datalet</name>
            <type>timeline</type>
            <idm>
                <inputs>
                    <input>
                        <name>TIMELINEinfo</name>
                        <description>infodescription</description>
                        <type>TEXT</type>
                        <selection>1</selection>
                    </input>
                    <input>
                        <name>TIMELINEname</name>
                        <description>namedescription</description>
                        <type>TEXT</type>
                        <selection>1</selection>
                    </input>
                    <input>
                        <name>TIMELINEdescription</name>
                        <description>eventdescriptiondescription</description>
                        <type>TEXT</type>
                        <selection>1</selection>
                    </input>
                    <input>
                        <name>TIMELINEmedia</name>
                        <description>latitudelongitudedescription</description>
                        <type>TEXT</type>
                        <selection>1</selection>
                    </input>
                    <input>
                        <name>TIMELINEstartdate</name>
                        <description>startdatedescription</description>
                        <type>TEXT</type>
                        <selection>1</selection>
                    </input>
                    <input>
                        <name>TIMELINEenddate</name>
                        <description>enddatedescription</description>
                        <type>TEXT</type>
                        <selection>?</selection>
                    </input>
                </inputs>
            </idm>
        </component>
```
Also, you should add in "\Datalet-Ecosystem-Provider\deep-components\locales\controllet_ln.js" the proper translation for the controllet (english and italian):
```javascript
//timeline
ln["timeline_it"] = "Timeline";
ln["timeline_en"] = "Timeline";
ln["TIMELINEinfo_en"] = "Additional Information";
ln["TIMELINEinfo_it"] = "Informazioni Addizionali";
ln["infodescription_en"] = "Additional Information";
ln["infodescription_it"] = "Informazioni Addizionali";
ln["TIMELINEname_en"] = "Event Name";
ln["TIMELINEname_it"] = "Nome dell'evento";
ln["namedescription_en"] = "Event Name";
ln["namedescription_it"] = "Nome dell'evento";
ln["TIMELINEdescription_en"] = "Event Description";
ln["TIMELINEdescription_it"] = "Descrizione dell'evento";
ln["eventdescriptiondescription_en"] = "Event Description";
ln["eventdescriptiondescription_it"] = "Descrizione dell'evento";
ln["TIMELINEmedia_en"] = "URL Media or Coordinates";
ln["TIMELINEmedia_it"] = "URL Multimediale o Coordinate";
ln["latitudelongitudedescription_en"] = "Event Coordinates or Media URL";
ln["latitudelongitudedescription_it"] = "Coordinate Geografiche dell'Evento o link a contenuto multimediale";
ln["TIMELINEstartdate_en"] = "Event Start Date";
ln["TIMELINEstartdate_it"] = "Data di Inizio dell'Evento";
ln["startdatedescription_en"] = "Event Start Date";
ln["startdatedescription_it"] = "Data di Inizio dell'Evento";
ln["TIMELINEenddate_en"]="Event End Date";
ln["TIMELINEenddate_it"]="Data di Fine dell'Evento";
ln["enddatedescription_en"] = "Event End Date";
ln["enddatedescription_it"] = "Data di Fine dell'Evento";
```
