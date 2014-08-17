<?xml version="1.0"?>
<RDF xmlns="http://www.w3.org/1999/02/22-rdf-syntax-ns#" xmlns:em="http://www.mozilla.org/2004/em-rdf#">
	
	<Description about="urn:mozilla:install-manifest">
		<em:id>better-bibtex@iris-advies.com</em:id>
		<em:name>Zotero Better Bib(La)Tex</em:name>
		<em:version>0.6.33</em:version>
    <em:description>Make Zotero useful for us LaTeX holdouts. More info @ https://github.com/ZotPlus/zotero-better-bibtex</em:description>
		<em:creator>Emiliano Heyns</em:creator>
		<em:updateURL>https://zotplus.github.io/better-bibtex/update.rdf</em:updateURL>
		<em:type>2</em:type> <!-- type=extension -->

		<!-- Requires Zotero -->
		<em:requires>
			<Description>
				<em:id>zotero@chnm.gmu.edu</em:id>
				<em:name>Zotero</em:name>
				<em:homepageURL>http://www.zotero.org</em:homepageURL>
				<em:minVersion>3.0</em:minVersion>
				<em:maxVersion>4.0.*</em:maxVersion>
			</Description>
		</em:requires>
    
		<!-- Requires Firefox or Zotero Standalone -->
		<em:targetApplication>
			<Description>
				<em:id>{ec8030f7-c20a-464f-9b0e-13a3a9e97384}</em:id>
				<em:minVersion>17.0</em:minVersion>
				<em:maxVersion>24.*</em:maxVersion>
			</Description>
		</em:targetApplication>
		<em:targetApplication>
			<Description>
				<em:id>zotero@chnm.gmu.edu</em:id>
				<em:minVersion>3.0</em:minVersion>
				<em:maxVersion>4.0.*</em:maxVersion>
			</Description>
		</em:targetApplication>
	</Description>
</RDF>
