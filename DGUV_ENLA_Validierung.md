#### Übersicht der validierten ENLA Profile

:running:  vollständig validiert!
:ambulance: validiert aber mit VS/CS Anmerkungen bzw. Problemen​

30 Profile ohne Bundle und Composition

[Arbeitsunfähigkeit](#Arbeitsunfähigkeit) :running:
[Aufenthaltsinformationen](#Aufenthaltsinformationen) :ambulance:
[AufnahmeBefunde](#AufnahmeBefunde) :ambulance:
[BehandelndeEinrichtung](#BehandelndeEinrichtung) :running:
[BehandlungsVerlauf](#BehandlungsVerlauf) :running:
[BesondereMassnahme](#BesondereMassnahme) :ambulance:
[DArzt](#DArzt) :ambulance:
[DArztOrganisation](#DArztOrganisation) :running:
[Datenschutz](#Datenschutz) :running:
[DiagnoseFreitext](#DiagnoseFreitext) :running:
[DiagnoseStrukturiert](#DiagnoseStrukturiert) :running:
[Entlassbefunde](#Entlassbefunde) :running:
[Heilmittel](#Heilmittel) :ambulance:
[Hilfsmittel](#Hilfsmittel) :ambulance:
[Konsiliarbefunde](#Konsiliarbefunde) :ambulance:
[Krankenkasse](#Krankenkasse) :running:
[Leistungserbringer](#Leistungserbringer) :running:
[MedikationArzneimittel](#MedikationArzneimittel)
[MedikationRezeptur](#MedikationRezeptur)
[MedikationsInformation](#MedikationsInformation)
[MedikationWirkstoff](#MedikationWirkstoff)
[Pflegekasse](#Pflegekasse)
[Wiedereingliederung](#stufenweiseWiedereingliederung)
[Therapieempfehlung](#Therapieempfehlung)
[Unfallbetrieb](#Unfallbetrieb)
[Unfallereignis](#Unfallereignis) :running:
[VersichertePerson](#VersichertePerson)
[WeiterbehandelndeOrganisation](#WeiterbehandelndeOrganisation)
[WeiterbehandelnderArzt](#WeiterbehandelnderArzt) :ambulance:



#### Validierungsergebnisse



<a id="Arbeitsunfähigkeit">Arbeitsunfähigkeit</a>

| Art              | Bezeichnung                                                  | Bemerkung |
| ---------------- | ------------------------------------------------------------ | --------- |
| Beispieldatei    | DGUV-ENLA-Bsp-Arbeitsunfaehigkeit.xml - DGUV-ENLA-Bsp-Arbeitsunfaehigkeit_1.xml |           |
| Profil           | Arbeitsunfähigkeit.xml                                       |           |
| Code Set(s)      |                                                              |           |
| Value Set(s)     |                                                              |           |
| Basis Profil(e): |                                                              |           |
| Constraints:     |                                                              |           |
| Validiert am:    | 30.09.2025                                                   |           |

**Validiert am: 30.09.2025**

```
DGUV-ENLA-Bsp-Arbeitsunfaehigkeit.xml
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Arbeitsunfaehigkeit.xml 02:40:03
[2, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[10, 9] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
[52, 25] Observation.value.ofType(CodeableConcept): Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Arbeitsunfaehigkeit|0.0.2


 DGUV-ENLA-Bsp-Arbeitsunfaehigkeit_1.xml
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Arbeitsunfaehigkeit_1.xml 02:58:03
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[24, 9] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
[55, 25] Observation.value.ofType(CodeableConcept): Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Arbeitsunfaehigkeit|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```




<a id="Aufenthaltsinformationen">Aufenthaltsinformationen</a>

| Art              | Bezeichnung                                                  | Bemerkung |
| ---------------- | ------------------------------------------------------------ | --------- |
| Beispieldatei    | DGUV_ENLA_Bsp_Aufenthaltsinformationen_1.xml - DGUV_ENLA_Bsp_Aufenthaltsinformationen_7.xml |           |
| Profil           | Aufenthaltsinformationen.xml                                 |           |
| Code Set(s)      |                                                              |           |
| Value Set(s)     |                                                              |           |
| Basis Profil(e): |                                                              |           |
| Constraints:     |                                                              |           |
| Validiert am:    | 26.09.2025                                                   |           |

**Validiert am: 26.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Aufenthaltsinformationen_1.xml 11:31:54
[1, 40] Encounter: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[20, 22] Encounter.hospitalization.admitSource: Information - !!Keiner der angegebenen Codes ist im Valueset 'Admit source' (http://hl7.org/fhir/ValueSet/encounter-admit-source|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Aufnahmeart#EB)
[27, 31] Encounter.hospitalization.dischargeDisposition: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-EntlassungsVerlegungsgrund|0.0.2

```

**Validiert am: xx.xx.xxxx**

```

```





 <a id="AufnahmeBefunde">AufnahmeBefunde</a>

| Art              | Bezeichnung                        | Bemerkung |
| ---------------- | ---------------------------------- | --------- |
| Beispieldatei    | DGUV_Basis_Bsp_Aufnahmebefunde.xml |           |
| Profil           | DGUV_Basis_PR_Aufnahmebefunde.xml  |           |
| Code Set(s)      |                                    |           |
| Value Set(s)     |                                    |           |
| Basis Profil(e): |                                    |           |
| Constraints:     |                                    |           |
| Validiert am:    | 30.09.2025                         |           |

**Validierung: 30.09.2025**

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_AufnahmeBefunde.xml 11:59:09
[15, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 15] Observation.category[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Observation Category Codes' (http://hl7.org/fhir/ValueSet/observation-category|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie#vitalparameter)
[26, 17] Observation.category[0].coding[0]: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie|0.0.2
[34, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="BehandelndeEinrichtung">BehandelndeEinrichtung</a>

| Art              | Bezeichnung                | Bemerkung |
| ---------------- | -------------------------- | --------- |
| Beispieldatei    | BehandelndeEinrichtung.xml |           |
| Profil           | BehandelndeEinrichtung.xml |           |
| Code Set(s)      |                            |           |
| Value Set(s)     |                            |           |
| Basis Profil(-e) |                            |           |
| Constraints:     |                            |           |
| Validiert am:    | 30.09.2025                 |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_BehandelndeEinrichtung.xml 02:23:45
[15, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="BehandlungsVerlauf">BehandlungsVerlauf</a>

| Art              | Bezeichnung                          | Bemerkung |
| ---------------- | ------------------------------------ | --------- |
| Beispieldatei    | DGUV_ENLA_Bsp_Behandlungsverlauf.xml |           |
| Profil           | DGUV_ENLA_PR_BehandlungsVerlauf.xml  |           |
| Code Set(s)      |                                      |           |
| Value Set(s)     |                                      |           |
| Basis Profil(-e) |                                      |           |
| Constraints:     | Keine                                |           |
| Validiert am:    | 30.0.9.2025                          |           |

**Validiert am: 30.0.9.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_BehandlungsVerlauf.xml 08:49:16
[10, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[10, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[28, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="BesondereMassnahme">BesondereMassnahme</a>

| Art              | Bezeichnung             | Bemerkung |
| ---------------- | ----------------------- | --------- |
| Beispieldatei    | BesondereMassnahme.xml  |           |
| Profil           | BesondereMassnahmen.xml |           |
| Code Set(s)      |                         |           |
| Value Set(s)     |                         |           |
| Basis Profil(-e) |                         |           |
| Constraints:     |                         |           |
| Validiert am:    | 30.09.2025              |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_BesondereMassnahmen.xml 09:21:47
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
[40, 15] Observation.effective.ofType(Timing).code: Information - !!Keiner der angegebenen Codes ist im Valueset 'TimingAbbreviation' (http://hl7.org/fhir/ValueSet/timing-abbreviation|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-MassnahmenZeitpunkt#Festzul)
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="DArzt">DArzt</a>

| Art              | Bezeichnung | Bemerkung |
| ---------------- | ----------- | --------- |
| Beispieldatei    | DArzt.xml   |           |
| Profil           | DArzt.xml   |           |
| Code Set(s)      |             |           |
| Value Set(s)     |             |           |
| Basis Profil(-e) |             |           |
| Constraints:     |             |           |
| Validiert am:    | 30.09.2025  |           |

**Validierung: 30.09.2025**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_DArzt.xml 11:08:25
[10, 47] PractitionerRole: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[37, 14] PractitionerRole.specialty[0].coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE' version '1.03' could not be found, so the code cannot be validated. Valid versions: []
[37, 14] PractitionerRole.specialty[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Practice Setting Code Value Set' (http://hl7.org/fhir/ValueSet/c80-practice-codes|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_BAR2_ARZTNRFACHGRUPPE#01)
[38, 13] PractitionerRole.specialty[0].coding[0]: Information - !!Dieses Element stimmt mit keinem bekannten Slicedefined in the profile http://fhir.dguv.de/ENLA/PractitionerRole/DGUV-ENLA-PR-DArzt|0.0.2 überein.
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="DArztOrganisation">DArztOrganisation</a>

| Art              | Bezeichnung           | Bemerkung |
| ---------------- | --------------------- | --------- |
| Beispieldatei    | ---                   |           |
| Profil           | DArztOrganisation.xml |           |
| Code Set(s)      |                       |           |
| Value Set(s)     |                       |           |
| Basis Profil(-e) |                       |           |
| Constaints:      |                       |           |
| Validiert am:    | 30.09.2025            |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_DArztOrganisation.xml 03:13:59
[15, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Datenschutz">Datenschutz</a>

| Art              | Bezeichnung     | Bemerkung |
| ---------------- | --------------- | --------- |
| Beispieldatei    | ----            |           |
| Profil           | Datenschutz.xml |           |
| Code Set(s)      |                 |           |
| Value Set(s)     |                 |           |
| Basis Profil(-e) |                 |           |
| Constraints:     |                 |           |
| Validiert am:    | 30.09.2025      |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Datenschutz.xml 10:24:38
[15, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2

```

**Validiert am: xx.xx.xxxx**

```

```





<a id="DiagnoseFreitext">DiagnoseFreitext</a>

| Art            | Bezeichnung          | Bemerkung |
| -------------- | -------------------- | --------- |
| Beispieldatei  | ---                  |           |
| Profil         | DiagnoseFreitext.xml |           |
| Code Set(s)    |                      |           |
| Value Set(s)   |                      |           |
| Basis Profile: |                      |           |
| Constraints:   |                      |           |
| Validiert am:  | 30.09.2025           |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_DiagnoseFreitext.xml 03:05:33
[7, 41] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)

```

**Validiert am: xx.xx.xxxx**

```

```





<a id="DiagnoseStrukturiert">DiagnoseStrukturiert</a>

| Art              | Bezeichnung              | Bemerkung |
| ---------------- | ------------------------ | --------- |
| Beispieldatei    | ---                      |           |
| Profil           | DiagnoseStrukturiert.xml |           |
| Code Set(s)      |                          |           |
| Value Set(s)     |                          |           |
| Basis Profil(-e) |                          |           |
| Constraints:     |                          |           |
| Validiert am:    | 30.09.2025               |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_DiagnoseStrukturiert.xml 12:15:15
[15, 40] Condition: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[22, 11] Condition.code.coding[0].system: Warning - A definition for CodeSystem 'http://fhir.de/CodeSystem/bfarm/icd-10-gm' version '2019' could not be found, so the code cannot be validated. Valid versions: []

```

**Validiert am: xx.xx.xxxx**

```

```





<a id="DokumentReferenz">DokumentReferenz</a>

| Art              | Bezeichnung                        | Bemerkung |
| ---------------- | ---------------------------------- | --------- |
| Beispieldatei    | DGUV_ENLA_Bsp_DokumentReferenz.xml |           |
| Profil           | DGUV_ENLA_PR_DokumentReferenz.xml  |           |
| Code Set(s)      |                                    |           |
| Value Set(s)     |                                    |           |
| Basis Profil(-e) |                                    |           |
| Constraints:     |                                    |           |
| Validiert am:    | 30.09.2025                         |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_DokumentenReferenz.xml 12:33:50
[15, 48] DocumentReference: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="Entlassbefunde">Entlassbefunde</a>

| Art              | Bezeichnung        | Bemerkung |
| ---------------- | ------------------ | --------- |
| Beispieldatei    | ---                |           |
| Profil           | Entlassbefunde.xml |           |
| Code Set(s)      |                    |           |
| Value Set(s)     |                    |           |
| Basis Profil(-e) |                    |           |
| Constraints:     |                    |           |
| Validiert am:    | 30.09.2025         |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Entlassbefunde.xml 03:22:53
[15, 42] Observation: Warning - !!Alle Observations sollten ein effectiveDateTime oder eine effectivePeriode haben
[15, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 15] Observation.category[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Observation Category Codes' (http://hl7.org/fhir/ValueSet/observation-category|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie#vitalparameter)
[26, 17] Observation.category[0].coding[0]: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie|0.0.2
[34, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="Heilmittel">Heilmittel</a>

| Art              | Bezeichnung    | Bemerkung |
| ---------------- | -------------- | --------- |
| Beispieldatei    | Heilmittel.xml |           |
| Profil           | Heilmittel.xml |           |
| Code Set(s)      |                |           |
| Value Set(s)     |                |           |
| Basis Profil(-e) |                |           |
| Constraints:     |                |           |
| Validiert am:    | 30.09.2025     |           |

**Validierung: 30.09.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Heilmittel.xml 03:31:38
[7, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[7, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[17, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
[32, 15] Observation.effective.ofType(Timing).code: Information - !!Keiner der angegebenen Codes ist im Valueset 'TimingAbbreviation' (http://hl7.org/fhir/ValueSet/timing-abbreviation|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-MassnahmenZeitpunkt#Festzul)
[42, 27] Observation.value.ofType(CodeableConcept): Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Heilmittel|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="Hilfsmittel">Hilfsmittel</a>

| Art              | Bezeichnung     | Bemerkung |
| ---------------- | --------------- | --------- |
| Beispieldatei    | Hilfsmittel.xml |           |
| Profil           | Hilfsmittel.xml |           |
| Code Set(s)      |                 |           |
| Value Set(s)     |                 |           |
| Basis Profil(-e) |                 |           |
| Constraints:     |                 |           |
| Validiert am:    | 30.09.2025      |           |

**Validierung: 30.09.2025**

```
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Hilfsmittel.xml 03:39:51
[15, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
[40, 15] Observation.effective.ofType(Timing).code: Information - !!Keiner der angegebenen Codes ist im Valueset 'TimingAbbreviation' (http://hl7.org/fhir/ValueSet/timing-abbreviation|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-MassnahmenZeitpunkt#Festzul)
[50, 27] Observation.value.ofType(CodeableConcept): Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Hilfsmittel|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="Konsiliarbefunde">Konsiliarbefunde</a>

| Art              | Bezeichnung          | Bemerkung |
| ---------------- | -------------------- | --------- |
| Beispieldatei    | ---                  |           |
| Profil           | Konsiliarbefunde.xml |           |
| Code Set(s)      |                      |           |
| Value Set(s)     |                      |           |
| Basis Profil(-e) |                      |           |
| Constraints:     |                      |           |
| Validiert am:    | 01.10.2025           |           |

**Validierung: 01.10.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Konsiliarbefunde.xml 07:34:44
[2, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[2, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[25, 15] Observation.category[0]: Information - !!Keiner der angegebenen Codes ist im Valueset 'Observation Category Codes' (http://hl7.org/fhir/ValueSet/observation-category|4.0.1), und es wird empfohlen, einen Code aus dieserm Valueset zu verwenden) (Codes = http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie#vitalparameter)
[26, 17] Observation.category[0].coding[0]: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-BefundKategorie|0.0.2
[34, 11] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/ENLA/CodeSystem/DGUV-ENLA-CS-Teilberichtsinhalt|0.0.2
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="Krankenkasse">Krankenkasse</a>

| Art              | Bezeichnung      | Bemerkung |
| ---------------- | ---------------- | --------- |
| Beispieldatei    | Krankenkasse.xml |           |
| Profil           | Krankenkasse.xml |           |
| Code Set(s)      |                  |           |
| Value Set(s)     |                  |           |
| Basis Profil(-e) |                  |           |
| Constraints:     |                  |           |
| Validiert am:    | 01.10.2025       |           |

**Validierung: 01.10.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Krankenkasse.xml 07:47:26
[15, 43] Organization: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Leistungserbringer">Leistungserbringer</a>

| Art              | Bezeichnung                          | Bemerkung |
| ---------------- | ------------------------------------ | --------- |
| Beispieldatei    | DGUV_ENLA_Bsp_Leistungserbringer.xml |           |
| Profil           | DGUV_ENLA_PR_Leistungserbringer.xml  |           |
| Code Set(s)      |                                      |           |
| Value Set(s)     |                                      |           |
| Basis Profil(-e) |                                      |           |
| Constraints:     |                                      |           |
| Validiert am:    | 01.10.2025                           |           |

**Validierung: 01.10.2025**

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Leistungserbringer.xml 08:19:10
[1, 43] Practitioner: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="MedikationArzneimittel">MedikationArzneimittel</a>

| Art              | Bezeichnung                | Bemerkung |
| ---------------- | -------------------------- | --------- |
| Beispieldatei    | MedikationArzneimittel.xml |           |
| Profil           | MedikationArzneimittel.xml |           |
| Code Set(s)      |                            |           |
| Value Set(s)     |                            |           |
| Basis Profil(-e) |                            |           |
| Constraints:     |                            |           |
| Validiert am:    | 01.10.2025                 |           |

**Validierung: **  01.10.2025

```
----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_MedikationArzneimittel.xml 08:50:07
[15, 41] Medication: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[22, 13] Medication.code.coding[0].system: Warning - A definition for CodeSystem 'http://fhir.de/CodeSystem/ifa/pzn' could not be found, so the code cannot be validated
[39, 13] Medication.form.coding[0].system: Warning - A definition for CodeSystem 'https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_KBV_DARREICHUNGSFORM' version '1.15' could not be found, so the code cannot be validated. Valid versions: []
[40, 17] Medication.form.coding[0]: Information - !!!!!!!!Das CodeSystem https://fhir.kbv.de/CodeSystem/KBV_CS_SFHIR_KBV_DARREICHUNGSFORM ist unbekannt
[40, 17] Medication.form.coding[0]: Warning - !!ValueSet https://fhir.kbv.de/ValueSet/KBV_VS_SFHIR_KBV_DARREICHUNGSFORM vom Validator nicht gefunden
```

**Validiert am: xx.xx.xxxx**

```

```





<a id="MedikationRezeptur">MedikationRezeptur</a>

| Art              | Bezeichnung            | Bemerkung |
| ---------------- | ---------------------- | --------- |
| Beispieldatei    | MedikationRezeptur.xml |           |
| Profil           | MedikationRezeptur.xml |           |
| Code Set(s)      |                        |           |
| Value Set(s)     |                        |           |
| Basis Profil(-e) |                        |           |
| Constraints:     |                        |           |
| Validiert am:    |                        |           |

**Validierung: xx.xx.xxxx** 

```

```

**Validiert am: xx.xx.xxxx**

```

```





<a id="MedikationsInformation">MedikationsInformation</a>

| Art              | Bezeichnung                | Bemerkung |
| ---------------- | -------------------------- | --------- |
| Beispieldatei    | MedikationsInformation.xml |           |
| Profil           | MedikationsInformation.xml |           |
| Code Set(s)      |                            |           |
| Value Set(s)     |                            |           |
| Basis Profil(-e) |                            |           |
| Constraints:     |                            |           |
| Validiert am:    |                            |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="MedikationWirkstoff">MedikationWirkstoff</a>

| Art              | Bezeichnung             | Bemerkung |
| ---------------- | ----------------------- | --------- |
| Beispieldatei    | MedikationWirkstoff.xml |           |
| Profil           | MedikationWirkstoff.xml |           |
| Code Set(s)      |                         |           |
| Value Set(s)     |                         |           |
| Basis Profil(-e) |                         |           |
| Constraints:     |                         |           |
| Validiert am:    |                         |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Pflegekasse">Pflegekasse</a>

| Art              | Bezeichnung     | Bemerkung |
| ---------------- | --------------- | --------- |
| Beispieldatei    | Pflegekasse.xml |           |
| Profil           | Pflegekasse.xml |           |
| Code Set(s)      |                 |           |
| Value Set(s)     |                 |           |
| Basis Profil(-e) |                 |           |
| Constraints:     |                 |           |
| Validiert am:    |                 |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```





<a id="PrognoseWiederaufnahmeTaetigkeit">PrognoseWiederaufnahmeTaetigkeit</a>

| Art              | Bezeichnung                          | Bemerkung |
| ---------------- | ------------------------------------ | --------- |
| Beispieldatei    | PrognoseWiederaufnahmeTaetigkeit.xml |           |
| Profil           | PrognoseWiederaufnahmeTaetigkeit.xml |           |
| Code Set(s)      |                                      |           |
| Value Set(s)     |                                      |           |
| Basis Profil(-e) |                                      |           |
| Constraints:     |                                      |           |
| Validiert am:    |                                      |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="RehaMassnahme">RehaMassnahme</a>

| Art              | Bezeichnung       | Bemerkung |
| ---------------- | ----------------- | --------- |
| Beispieldatei    | RehaMassnahme.xml |           |
| Profil           | RehaMassnahme.xml |           |
| Code Set(s)      |                   |           |
| Value Set(s)     |                   |           |
| Basis Profil(-e) |                   |           |
| Constraints:     |                   |           |
| Validiert am:    |                   |           |

**Validierung: xx.xx.xxxx**

```


```

**Validiert am: xx.xx.xxxx**

```

```



<a id="stufenweiseWiedereingliederung">stufenweiseWiedereingliederung</a>

| Art              | Bezeichnung                        | Bemerkung |
| ---------------- | ---------------------------------- | --------- |
| Beispieldatei    | stufenweiseWiedereingliederung.xml |           |
| Profil           | stufenweiseWiedereingliederung.xml |           |
| Code Set(s)      |                                    |           |
| Value Set(s)     |                                    |           |
| Basis Profil(-e) |                                    |           |
| Constraints:     |                                    |           |
| Validiert am:    |                                    |           |

**Validierung: 30.05.2025**

```


```



**Validiert am: xx.xx.xxxx**

```

```





<a id="Therapie">Therapie</a>

| Art              | Bezeichnung  | Bemerkung |
| ---------------- | ------------ | --------- |
| Beispieldatei    | Therapie.xml |           |
| Profil           | Therapie.xml |           |
| Code Set(s)      |              |           |
| Value Set(s)     |              |           |
| Basis Profil(-e) |              |           |
| Constraints:     |              |           |
| Validiert am:    |              |           |

**Validierung: xx.xx.xxxx**

```


```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Therapieempfehlung">Therapieempfehlung</a>

| Art              | Bezeichnung            | Bemerkung |
| ---------------- | ---------------------- | --------- |
| Beispieldatei    | Therapieempfehlung.xml |           |
| Profil           | Therapieempfehlung.xml |           |
| Code Set(s)      |                        |           |
| Value Set(s)     |                        |           |
| Basis Profil(-e) |                        |           |
| Constraints:     |                        |           |
| Validiert am:    |                        |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Unfallbetrieb">Unfallbetrieb</a>

| Art              | Bezeichnung       | Bemerkung |
| ---------------- | ----------------- | --------- |
| Beispieldatei    | Unfallbetrieb.xml |           |
| Profil           | Unfallbetrieb.xml |           |
| Code Set(s)      |                   |           |
| Value Set(s)     |                   |           |
| Basis Profil(-e) |                   |           |
| Constraints:     |                   |           |
| Validiert am:    |                   |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Unfallereignis">Unfallereignis</a>

| Art              | Bezeichnung        | Bemerkung |
| ---------------- | ------------------ | --------- |
| Beispieldatei    | Unfallereignis.xml |           |
| Profil           | Unfallereignis.xml |           |
| Code Set(s)      |                    |           |
| Value Set(s)     |                    |           |
| Basis Profil(-e) |                    |           |
| Constraints      |                    |           |
| Validiert am:    |                    |           |

**Validierung: 26.09.2025**

```

----------------------------------------------------------------------------------
C:\Users\Ext.Matten.Friedhelm\sources\repos\DGUV-ENLA\DGUV_ENLA_Bsp_Unfallereignis.xml 02:14:35
[15, 42] Observation: Warning - !!Alle Observations sollten einen Performer haben
[15, 42] Observation: Warning - Constraint failed: dom-6: 'A resource should have narrative for robust management' (defined in http://hl7.org/fhir/StructureDefinition/DomainResource) (Best Practice Recommendation)
[37, 9] Observation.code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-Verletzungsartenverzeichnis|1.3
[55, 11] Observation.component[0].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[67, 11] Observation.component[1].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[79, 11] Observation.component[2].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
[91, 11] Observation.component[3].code: Information - Reference to draft CodeSystem http://fhir.dguv.de/Basis/CodeSystem/DGUV-Basis-CS-UnfallereignisComponents|1.3
```

**Validiert am: xx.xx.xxxx**

```

```



<a id="Unfallversicherungstraeger">Unfallversicherungstraeger</a>

| Art              | Bezeichnung                    | Bemerkung |
| ---------------- | ------------------------------ | --------- |
| Beispieldatei    | Unfallversicherungstraeger.xml |           |
| Profil           | Unfallversicherungstraeger.xml |           |
| Code Set(s)      |                                |           |
| Value Set(s)     |                                |           |
| Basis Profil(-e) |                                |           |
| Constraints:     |                                |           |
| Validiert am:    |                                |           |

**Validierung: xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="VersichertePerson">VersichertePerson</a>

| Art              | Bezeichnung           | Bemerkung |
| ---------------- | --------------------- | --------- |
| Beispieldatei    | VersichertePerson.xml |           |
| Profil           | VersichertePerson.xml |           |
| Code Set(s)      |                       |           |
| Value Set(s)     |                       |           |
| Basis Profil(-e) |                       |           |
| Constraints:     |                       |           |
| Validiert am:    |                       |           |

**Validierung:** **xx.xx.xxxx**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="WeiterbehandelndeOrganisation">WeiterbehandelndeOrganisation</a>

| Art              | Bezeichnung                       | Bemerkung |
| ---------------- | --------------------------------- | --------- |
| Beispieldatei    | ---                               |           |
| Profil           | WeiterbehandelndeOrganisation.xml |           |
| Code Set(s)      |                                   |           |
| Value Set(s)     |                                   |           |
| Basis Profil(-e) |                                   |           |
| Constraints:     |                                   |           |
| Validiert am:    |                                   |           |

**Validierung:**

```

```

**Validiert am: xx.xx.xxxx**

```

```



<a id="WeiterbehandelnderArzt">WeiterbehandelnderArzt</a>

| Art              | Bezeichnung                              | Bemerkung |
| ---------------- | ---------------------------------------- | --------- |
| Beispieldatei    | DGUV_ENLA_Bsp_WeiterbehandelnderArzt.xml |           |
| Profil           | DGUV_ENLA_PR_WeiterbehandelnderArzt.xml  |           |
| Code Set(s)      |                                          |           |
| Value Set(s)     |                                          |           |
| Basis Profil(-e) |                                          |           |
| Constraints:     |                                          |           |
| Validiert am:    |                                          |           |

**Validierung: xx.xx.xxxx** 

```

```

**Validiert am: xx.xx.xxxx**

```

```



