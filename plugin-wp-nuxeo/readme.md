# Plugin Nuxeo pour Wordpress

**Contributors**:       [nuxeo](http://www.nuxeo.com/)  
**Tags**:               automation, nuxeo  
**Requires at least**:  4.1.4
**Tested up to**:       4.2.1  
**Plugin URI**:         http://www.nuxeo.com/  
**Version**:            0.0.1-snapshot  
**Author**:             Nuxeo  
**Author URI**:         http://www.nuxeo.com/  
**License**:            LGPLv3  

## Description

WordPress Nuxeo integration through the use of a shortcode.

## Installation

### Manual

Manual installation through the Plugins panel of WordPress.

## Usage

Configuration des options du plugins.
Utilisation du shortcode [cmis] avec les paramètres suivants :
* folder="/my particular/folder name/" 				# Chemin du répertoire complet sous la racine de Corum
* etablissement="CROUS01"   						# Indication de l'établissement cible
* partage="Partage"                					# Indicateur du niveau Partage
* service="Service Courrier"						# Indicateur de service sour le CROUS courant
* name="Agenda%.doc"            					# Nom du document (pouvant inclure des caractères génériques)
* doc_id="c5e890d3-87f5-42cb-abe4-1ed9d0d2600c"		# Permalink Nuxeo d'un document
* dossier_id="05cdeaa1-e57d-450a-8347-1600206e7cce"	# Permalink Nuxeo d'un dossier

## License

LGPLv3