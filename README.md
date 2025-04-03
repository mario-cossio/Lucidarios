# Lucidarios
**Repository of witnesses of the <em>Lucidario</em>**
[![DOI](https://zenodo.org/badge/568264531.svg)](https://doi.org/10.5281/zenodo.7388255)

This is a repository contains transcriptions of the nine witnesses of Sancho IV's <em>Lucidario</em>. The transcriptions are encoded using the [semi-paleographic system](http://www.hispanicseminary.org/manual-en.htm) of the Hispanic Seminary of Medieval Studies, as explained [here](https://lucidarios.hypotheses.org/transcripciones/normas-de-transcripcion):

<ol>
	<li>A (Biblioteca Nacional de España, ms. 3369)</li>
	<li>B (Biblioteca General Histórica, Universidad de Salamanca, ms. 1958)</li>
	<li>C (Real Biblioteca, ms. II/793)</li>
	<li>D (Real Academia Española, ms. 15, códice de Puñonrostro)</li>
	<li>E (Biblioteca Nacional de España, ms. 6958)</li>
	<li>F (Biblioteca General Histórica, Universidad de Salamanca, ms. 2401)</li>
	<li>G (Real Academia de la Historia, ms. 101)</li>
	<li>H (Bibliothèque patrimonial Villon, ms. A283)</li>
	<li>I (Biblioteca de la Fundación Bartolomé March Servera, ms. MA26-5-07)</li> 
</ol>

The repository also holds the transcription of the only medieval Spanish translation of Honorius Augustodunensis' <em>Elucidarium</em>, the <em>Lucidario romanceado</em>, preserved in the Biblioteca Histórica Marqués de Valdecilla of the Universidad Complutense de Madrid, ms. 148. The edition of this text was published in <em>Incipit</em> [issue 41](http://www.iibicrit-conicet.gov.ar/ojs/index.php/incipit/article/view/541).

*How to cite*:

<ol>
	<li>Cossío Olavide, Mario (2023). "<em>Lucidario</em>, witness A (Biblioteca Nacional de España, ms. 3369), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2024). "<em>Lucidario</em>, witness B (Biblioteca General Histórica de la Universidad de Salamanca, ms. 1958), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2022). "<em>Lucidario</em>, witness C (Real Biblioteca, ms. II/793), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2022). "<em>Lucidario</em>, witness D (Real Academia Española, ms. 15), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2022). "<em>Lucidario</em>, witness E (Biblioteca Nacional de España, ms. 6958), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2025). "<em>Lucidario</em>, witness F (Biblioteca General Histórica de la Universidad de Salamanca, ms. 2401), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2022). "<em>Lucidario</em>, witness G (Real Academia de la Historia, ms. 101), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2022). "<em>Lucidario</em>, witness H (Bibliothèque patrimonial Villon, ms. A283), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2023). "<em>Lucidario</em>, witness I (Biblioteca de la Fundación Bartolomé March Servera, ms. MA26-5-07), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
	<li>Cossío Olavide, Mario (2021). "<em>Lucidario romanceado</em> (Biblioteca Histórica Marqués de Valdecilla, Universidad Complutense de Madrid, ms. 148), semi-paleographic transcription". <em>Lucidarios, v. 0.5</em>, https://doi.org/10.5281/zenodo.7388255, date of access.</li>
</ol>

***Collatio***

This subfolder contains  materials for the <em>collatio</em> of the <em>Lucidario</em>, a work in progress for a critical edition in preparation. The documents are organized into folders with correlative numbers for each chapter, each containing up to four subfolders: `1. Textos`, `2. Colación`, `3. Rúbrica`, and `4. Edición` (or sometimes `3. Edición`).

<ol>
	<li><strong><code>Textos</code></strong>: This subfolder includes the transcriptions (organized by witness) of each chapter of the *Lucidario*, divided into three subfolders:</li>
		<ol>
			<li>`Marcados`: This folder includes the normalized transcriptions in Ms. Word *with* the original punctuation, page foliation, and a color code to highlight passages requiring editorial attention. If applicable, it also contains the transcription of the Latin translation, *F*. The color code is as follows:</li>
				<ul>
					<li>$${\color{red}Red}$$: Duplications or errors identified by the scribe (s), but not cancelled. Fully cancelled text is deleted from this version, and registered in the original semi-paleographic transcription file for the witness.</li>
					<li>$${\color{orange}Orange}$$: Text in Arabic, Hebrew, or Latin, or *lacunae*.</li>
					<li>$${\color{blue}Blue}$$: Additions or corrections made by medieval hands other from the main scribe(s).</li>
				</ul>
			<li>`Limpios`: This folder contains the normalized transcriptions in Ms. Word *without* punctuation, foliation, or color coding. All text previously highlighted in red has been removed.</li>
			<li>`Stylo`: This folder contains the normalized transcriptions in plain text format for stylometric analysis. All problematic passages (e.g., those containing question marks for unresolved characters or Latin quotes) have been resolved or removed.</li>
		</ol>
	</li>
	<li>`*Colación*`: This subfolder can contain up to five plain text files, which are versioned **ChrysoCollate** collation files (https://cental.uclouvain.be/chrysocollate):</li>
		<ol>
			<li>`Chapter Number+_separado`: This version contains all collated witnesses with their readings in separate, individual columns. There is no attempt to align witnesses that have extrapolated passages or additions not sustained by the rest of the tradition.</li>
			<li>`Chapter Number+_revisado`: Similar to `_separado`, but if the chapter is transmitted by witness D, all its extrapolations and additions are deleted and registered as notes. The rest of the text remains unchanged.</li>
			<li>`Chapter Number+_limpio`: This version contains all collated witnesses with their readings in separate, but all additions and extrapolations not supported by the tradition are deleted and recorded as notes.</li>
			<li>`Chapter Number+_unido`: This version is identical to `_limpio`, except all shared readings are displayed in joined columns.</li>
			<li>`Chapter Number+_editado`: This version contains the edited chapter (which may still be in progress).</li>
		</ol>
	</li>
	<li>`*Rúbrica*`: This subfolder contains a single Ms. Word document named `Rubrica+Chapter Number`, where all rubrics extracted from the chapters are compiled. If this subfolder does not exist, the chapter does not have a rubric in any of the witnesses. The document contains the definite (collated) title for the chapter, a complete list of the rubrics for the chapter found in each witness (including those from tables of contents) and from the Latin translation.</li>
	<li>`*Edición*` (or `*3. Edición*`, when the `*Rúbrica*` subfolder is absent): This subfolder contains up to two Ms. Word files:
		<ol>
			<li>`Chapter Number_inicial`: This is the initial collated chapter without punctuation, capitalization, or other text normalization, but with a complete critical apparatus in footnotes.</li>
			<li>`Chapter Number-F`: The collated chapter of the Latin translation, *F*, formatted according to editorial norms for classical Latin. In addition, red, italics and strikethrough ($${\color{red}*<s>text</s>*}$$) is used to mark editorial deletions by J.E. Nieremberg, and blue to mark $${\color{blue}text}$$ added by Nieremberg in the manuscript.</li>
		</ol>
	</li>
</ol>

*Nota Bene*: This work is ongoing, so not all chapters currently have all subfolders or files. They will be added progressively as the collation advances, with an estimated completion date of July 2026.

***Stylo***

This subfolder contains plain text files for stylometric analysis, organized by witness. The `Enteros` subfolder contains the same files as `3. Stylo` in the `*2. Colación*` folder. The main folder contains a single plain text document with the complete witness.

The chapters do not always follow their original manuscript order; instead, they are arranged according to the reconstructed *original* order intended for the edition. Passages in other languages (Latin, Hebrew, or Arabic) and scribal deletions have been excluded to prevent stylistic contamination. *This folder is not currently updated but will be as the process continues.*

**Scripts**

This subfolder contains various scripts for BBEdit, Mac Terminal, and R, along with a set of normalization criteria developed for the collatio of semi-paleographic transcriptions of medieval Spanish and Neo-Latin texts.

<p align="right">MCO</p>
<p align="right">Last update of Readme.md: April 3, 2025</p>
<p align="right">Latest Release (Lucidarios v. 0.5): March 20, 2025</p>
