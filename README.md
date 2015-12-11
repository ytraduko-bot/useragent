# UserAgent

UserAgent nutzt unter Anderem Mobile_Detect um zu erkennen mit welchem Browser, Betriebssystem und Gerätetyp der Besucher die Seite aufgerufen hat. Dabei liefert UserAgent diverse Informationen die aus dem mitgelieferten Header des Browsers aufbereitet werden.

<table width="100%">
	<tr>
		<th>Wert</th>
		<th>Beschreibung</th>
	</tr>
	<tr>
		<td width="150">$ua->class</td>
		<td>Liefert eine Klasse, die alle nötigen Informationen über den Browser enthält. Besonders geeignet als class-Attribut im HTML-Tag. <b>class="mac chrome webkit ch47 noTouch"</b></td>
	</tr>
	<tr>
		<td width="150">$ua->tablet</td>
		<td>Ist das Gerät ein Tablet: true | false</td>
	</tr>
	<tr>
		<td width="150">$ua->touch</td>
		<td>Beschreibung.</td>
	</tr>
	<tr>
		<td width="150">$ua->shorty</td>
		<td>Browser-Kürzel: ie, ff, ch</td>
	</tr>
	<tr>
		<td width="150">$ua->version</td>
		<td>Browser-Version: ie 8|9|10</td>
	</tr>
	<tr>
		<td width="150">$ua->engine</td>
		<td>Browser-Engine: gecko, trident, ...</td>
	</tr>
	<tr>
		<td width="150">$ua->mobile</td>
		<td>Mobile-Gerät: true | false.</td>
	</tr>
</table>