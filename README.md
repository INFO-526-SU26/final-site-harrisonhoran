[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/7LgAUKoA) \# project-final

Final Project repo for INFO 526 - Summer 2024.

#### Disclosure:

Derived from the original course by Mine Çetinkaya-Rundel \@ Duke University

## **Data Dictionary (provided by TidyTuesday)**

### **`endangered_status.csv`**

| **Variable** | **Class** | **Description**                                    |
|--------------|-----------|----------------------------------------------------|
| id           | character | Unique identifier for language                     |
| status_code  | character | Code of the agglomerated endangerment status (1–6) |
| status_label | character | Descriptive label of endangerment category         |

### **`families.csv`**

| **Variable** | **Class** | **Description**                       |
|--------------|-----------|---------------------------------------|
| id           | character | Unique identifier for language family |
| name         | character | Language family name                  |

### **`languages.csv`**

| **Variable** | **Class** | **Description** |
|----|----|----|
| id | character | Unique identifier for language |
| name | character | Language name |
| macroarea | character | General geographic area in which the language is found |
| latitude | double | Latitude of language location (as point) |
| longitude | double | Longitude of language location (as point) |
| iso639p3code | character | ISO 639-3 identifier of language (if available) |
| countries | character | Countries in which language is used (separated by ";") |
| is_isolate | logical | Whether language is an isolate (i.e. has no known relatives) |
| family_id | character | Unique identifier of family that the language is part of (if not isolate) |

### **`fam_lgs.csv`**

| **Variable** | **Class** | **Description** |
|:---|:---|:---|
| ID | character | Unique identifier for language |
| Name | character | Language name |
| Macroarea | character | General geographic area in which the language is found |
| Latitude | double | Latitude of language location (as point) |
| Longitude | double | Longitude of language location (as point) |
| Glottocode | character | Unique identifier from the Glottolog database (e.g., `stan1293`) |
| ISO639P3code | character | ISO 639-3 identifier of language (if available) |
| Level | character | Classificatory level of the entry (e.g., language, dialect, family) |
| Countries | character | Countries in which language is used (separated by ";") |
| Family_ID | character | Unique identifier of family that the language is part of (if not isolate) |
| Language_ID | character | Identifier for the parent language when the entry is a dialect or sub-variety |
| Closest_ISO369P3code | character | ISO 639-3 code of the most closely related language with a code, used when the entry itself lacks one |
| First_Year_Of_Documentation | double | Earliest year in which the language was recorded or documented |
| Last_Year_Of_Documentation | double | Most recent year in which the language was recorded or documented |
| Is_Isolate | logical | Whether language is an isolate (i.e. has no known relatives) |
