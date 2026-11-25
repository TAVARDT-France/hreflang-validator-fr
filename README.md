# Validateur de Balises Hreflang et SEO International

[![Validateur Hreflang](https://img.shields.io/badge/TAVARDT-Hreflang-5b3cf5.svg)](https://tools.tavardt.com/fr/validateur-balises-hreflang/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Audit de reciprocite des liens alternatifs, ciblage linguistique et territorial ISO, et architecture de repli global x-default.

Developpe et maintenu par la division de l ingeniere d indexation internationale et des standards web de **TAVARDT**.

***

## Capacites d Audit Hreflang et SEO International

* **Verification de Balise Auto-Referentielle**: Controle systematique de la presence de l URL courante parmi les cibles linguistiques alternatives.
* **Inspection de Repli x-default**: Validation de la balise par defaut pour les visiteurs hors des zones geographiques ciblees.
* **Validation des Codes ISO 639-1 et ISO 3166-1**: Controle strict de conformite des codes langue et pays pour eviter les erreurs d indexation regionale.
* **Concordance avec la Balise Canonique**: Detection des divergences critiques lorsque l URL canonique contredit les annotations hreflang.
* **Extraction Double Source**: Analyse conjointe des balises HTML `<head>` et des en-tetes de reponse HTTP Link.
* **Score d Integrite Internationale**: Note technique sur 100 classant la page en COMPLIANT, WARNING ou CRITICAL avec alertes directes.

***

## Installation et Execution

Necessite Python 3.8 ou superieur sans bibliotheques tierces.

```bash
git clone https://github.com/TAVARDT-France/hreflang-validator-fr.git
cd hreflang-validator-fr
python hreflang_validator.py https://societe.fr
```

Pour exporter les resultats au format JSON structure dans vos pipelines CI/CD:

```bash
python hreflang_validator.py https://societe.fr -j
```

***

## Diagnostic en Ligne

Pour des audits approfondis et des tests visuels de balisage international:

* [Validateur Hreflang](https://tools.tavardt.com/fr/validateur-balises-hreflang/)
* [Portail Institutionnel](https://ag.tavardt.com/fr/)

***

## Conseil en SEO International et Deploiement Global

Pour l architecture multilingue et l alignement avec les standards W3C, sollicitez l expertise de **TAVARDT**.

***

## Liens Utiles

* **Portail Institutionnel:** https://ag.tavardt.com/fr/
* **Suite de Diagnostic:** https://tools.tavardt.com/fr/
* **Contact Technique:** https://ag.tavardt.com/fr/contact/

***

### Licence
Distribue sous licence MIT. Consultez le fichier LICENSE pour plus d informations.

***

© 2026 TAVARDT. Tous droits reserves.
