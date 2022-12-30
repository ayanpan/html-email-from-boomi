# Send Email in HTML format from Boomi

## Boomi Implementation

Overall Boomi process is as below.

![a7](https://user-images.githubusercontent.com/12267939/210048220-619bdd6b-aa7b-42d6-8adc-0e3f1aa23697.JPG)

![a8](https://user-images.githubusercontent.com/12267939/210048232-41c48955-2171-4181-8365-29a87064b66f.JPG)

**Step-1:** Create sample error records (refer Sample_Error_Records.csv), split them, and set the properties.

![a1](https://user-images.githubusercontent.com/12267939/210048345-07fc87a3-4d20-4867-b2dd-b463866d4770.JPG)

![a2](https://user-images.githubusercontent.com/12267939/210048370-e308bfec-0755-40bd-baa9-500ada25edfa.JPG)

![a3](https://user-images.githubusercontent.com/12267939/210048404-92460a91-225e-4c96-b4c4-96974b14cb5a.JPG)

**Step-2:** Create table data/rows (refer Boomi_Table_Rows.html).

![a4](https://user-images.githubusercontent.com/12267939/210048432-59ea4d4d-8f0a-4036-9137-c79f501b74ab.JPG)

**Step-3:** Create HTML content (refer Boomi_Table.html).

![a5](https://user-images.githubusercontent.com/12267939/210048599-e7dcff6d-d6ef-40e8-9945-bcce4e41393e.JPG)

**Step-4:** Set email properties, with body as **Current Data**.

![a6](https://user-images.githubusercontent.com/12267939/210048913-10425c6c-eff1-4d9b-8414-17d181882fcf.JPG)

**Step-5:** Set **Disposition** as **Inline** and **Content Type** as **text/html**.

![a9](https://user-images.githubusercontent.com/12267939/210048929-f1c00c16-0ab8-472f-8e75-4b353b278920.JPG)

## Sample Email

![a10](https://user-images.githubusercontent.com/12267939/210049880-55fff3ab-56d2-4ce2-8f37-0c5af4eed43f.JPG)

## Note

If the intended email recipient(s) use **Gmail**, then use **inline style tags** because Gmail strips **CSS/style** from **head** tag.
