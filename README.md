# Extraire le texte

Extrayez du texte à partir de fichiers pour les rendre consultables et lisibles par machine.

Une fois installé et actif, ce module présente les caractéristiques suivantes:

- Le module ajoute une propriété "texte extrait" où il définit le texte extrait à
  médias et articles.
- Lors de l'ajout d'un média, le module extraira automatiquement le texte du fichier
  et définissez le texte sur le support.
- Lors de l’ajout ou de la modification d’un élément, le module regroupe automatiquement les
  texte multimédia (dans l'ordre) et définissez le texte sur l'élément.
- Lors de la mise à jour par lots d'éléments, l'utilisateur peut choisir d'actualiser le texte extrait.

## Formats de fichiers pris en charge:

- DOC (application / msword)
- DOCX (application / vnd.openxmlformats-officedocument.wordprocessingml.document)
- HTML (texte / html)
- PDF (application / pdf)
- RTF (application / RTF)
- TXT (text / plain)

## Extracteurs:

###Catdoc
Used to extract text from DOC and RTF files. Requires [catdoc](https://linux.die.net/man/1/catdoc).

### Doc2txt

Utilisé pour extraire du texte à partir de fichiers DOCX. Nécessite [doc2txt] (http://docx2txt.sourceforge.net/).

### Filegetcontents

Utilisé pour extraire du texte à partir de fichiers TXT. Aucune exigence.

### Lynx

Utilisé pour extraire du texte à partir de fichiers HTML. Nécessite [lynx] ​​(https://linux.die.net/man/1/lynx).

### Pdftotext

Utilisé pour extraire du texte à partir de fichiers PDF. Nécessite [pdftotext] (https://linux.die.net/man/1/pdftotext).
