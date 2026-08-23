TRNOVÁ – PRVNÍ VOLBA / VARIANTA D v42 S EDITOREM PRO IVANA

Tato verze vychází přímo z v41. Design, ikony a responzivita jsou v HTML/CSS zamčené.
Ivan upravuje pouze obsah přes /admin/.

CMS používá stejný mechanismus jako Cosmos:
- Decap CMS
- Netlify Identity
- Git Gateway
- branch main

Po propojení projektu dynamic s GitHub repozitářem:
1. Netlify > Identity > Enable Identity
2. Registration > Invite only
3. Services > Git Gateway > Enable Git Gateway
4. Pozvat Ivana e-mailem
5. Editor: https://VAŠE-DYNAMIC-ADRESA.netlify.app/admin/

DŮLEŽITÉ:
Web načítá texty z /content/*.json, proto lokální otevření index.html přes file:// není určeno
pro finální kontrolu obsahu. Na Netlify/GitHub bude fungovat standardně.
