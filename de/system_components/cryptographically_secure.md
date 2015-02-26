# Kryptographisch sicher
Im SAFE Netzwerk erstellen Vaults als erstes ein [Public-Key-Kryptosystem](http://de.wikipedia.org/wiki/Asymmetrisches_Kryptosystem) um dem Netzwerk beizutreten.

Diese Schlüssel werden verwendet um die  Kommunikation zwischen den einzelnen Vaults zu sichern.

Im Gegensatz zu traditionell gesicherten Kommunikationsmechanismen die einen Schlüsselaustausch (wie z.B. [Diffie Hellman](http://de.wikipedia.org/wiki/Diffie-Hellman-Schl%C3%BCsselaustausch)) vorraussetzen, stellt das SAFE Netzwerk diese Schlüssel den Vaults im [Routing](https://github.com/maidsafe/MaidSafe-Routing) Layer bereit.

Der Vorteil dabei ist das sogar kompromitierte Hardware durchlaufen werden und somit [Man-in-the-Middle-Angriffe](http://en.wikipedia.org/wiki/Man-in-the-middle_attack) verhindert.

Da jeder Vault Nachrichten zu und von jedem anderen Vault mit dem es kommuniziert entschlüsseln kann, wird die Sicherheit des ganzen Netzwerk gesteigert.
