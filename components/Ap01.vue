<template>
	<div>
		<div class="flex items-center justify-center">
			<div class="mt-16 h-full w-[300px] items-center justify-center md:w-[700px]">
				<div class="mb-16 flex">
					<h1 class="bg-gradient-to-r from-fuchsia-400 to-purple-600 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						Lucía Álvarez
					</h1>
					<h1 class="ml-auto bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						Institut Sapalomera
					</h1>
				</div>
				<div class="text-start">
					<h1 class="text-lg font-bold text-white lg:text-2xl">AP_01_Instal·lació de VirtualBox i configuració de VirtualBox</h1>
				</div>
				<hr class="mt-2 h-1 rounded border-0 bg-gradient-to-br from-white to-pink-500 md:w-[700px]" />
				<div id="instalacio-de-virtualbox">
					<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						1 - Instalació del VirtualBox
					</h1>
					<hr class="my-2 h-1 w-[240px] rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500 md:w-[245px] lg:w-[325px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Primer hem d'anar a la pàgina de virtualbox per descarregar l'executable de l'instal·lador, per això donar-li aquest botó per
						anar directament a la pàgina web de la descàrrega.
					</h1>
					<div>
						<a
							href="https://www.virtualbox.org/wiki/Downloads"
							target="_blank"
							class="group mb-2 mr-2 mt-2 inline-flex items-center justify-center overflow-hidden rounded-lg bg-gradient-to-br from-purple-600 to-blue-500 p-0.5 text-center text-sm font-medium text-gray-900 hover:text-white focus:outline-none focus:ring-4 focus:ring-blue-300 group-hover:from-purple-600 group-hover:to-blue-500 dark:text-white dark:focus:ring-blue-800"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								class="mx-2 h-6 w-6 transition-all duration-75 ease-in group-hover:bg-opacity-0"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M3 16.5v2.25A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75V16.5M16.5 12L12 16.5m0 0L7.5 12m4.5 4.5V3"
								/>
							</svg>

							<span
								class="rounded-md bg-white px-5 py-2.5 transition-all duration-75 ease-in group-hover:bg-opacity-0 dark:bg-gray-900"
							>
								Descarregar
							</span>
						</a>
					</div>
					<img src="/images/AP01-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja estem a la pàgina d'instal·lació hem d'escollir la nostra instal·lació preferida, si ets a windows o si estàs a
						linux agafaràs una o altra. Un cop escollida començarà la descàrrega de l'instal·lador executable.
					</h1>
					<img src="/images/AP02-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop acabat el fitxer estarà a la nostra carpeta de descàrregues.
					</h1>
					<img src="/images/AP03-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						L'executem, ens demanarà permisos d'administrador, donem que sí i ens sortirà aquesta pantalla:
					</h1>
					<img src="/images/AP04-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara li donem a "next"</h1>
					<img src="/images/AP05-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà quines funcions del programa volem instal·lar, normalment aquí no caldria tocar res, com a molt pots
						canviar on vols que se t'instal·li el programa, però no importa gaire. Quan ja hagis acabat de posar-ho al teu gust dóna-li a
						“next”.
					</h1>
					<img src="/images/AP06-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens sortirà un advertiment que quan iniciarem la descàrrega, la nostra connexió a internet s'aturarà un moment perquè s'ha
						de reiniciar, li donem que si i ens sortirà això:
					</h1>
					<img src="/images/AP07-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Donem a "install" i començarà la instal·lació de VirtualBox.</h1>
					<img src="/images/AP08-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop acabada la instal·lació ens sortirà aquesta pestanya dient que ja ha completat la instal·lació, donem a "finish" i
						se'ns obrirà el programa.
					</h1>
					<img src="/images/AP09-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
				<div id="configuració del virtualbox">
					<div class="w-full">
						<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
							2 - Configuració del VirtualBox
							<hr class="my-2 h-1 w-full rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
						</h1>
					</div>
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Per obrir el menú de preferències hem de donar-li a "<span class="font-bold">File > Preferences</span>" o també podem fer
						<span class="font-bold">CTRL</span> + <span class="font-bold">G</span>.
					</h1>
					<img src="/images/AP10-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP11-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim obert el menú de preferències podem veure que hi ha els apartats següents:
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">1 - General</h1>
					<img src="/images/AP11-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat general l'únic que hi ha és l'opció de seleccionar la carpeta on hi ha les teves màquines virtuals. Si la vols
						canviar selecciona la nova carpeta i dona-li a "ok".
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">2 - Input</h1>
					<img src="/images/AP12-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat input podem canviar el que fan les combinacions de segons quines tecles quan estem usant virtual box i quan estem
						en una màquina virtual. Si les vols canviar només selecciona la funció que vols posar-li una combinaion de tecles i per
						desar-lo dóna-li a "ok".
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">3 - Update</h1>
					<img src="/images/AP13-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat update podem posar cada quant volem que virtual box miri si hi ha una nova versió del programa i si hi ha una nova
						versió s'actualitzarà sol. Per activar-lo només selecciona l'opció "check for updateds" i selecciona cada quant vols que miri
						si hi ha una versió i per últim també pots seleccionar si vols que sigui una versió estable o que sigui totes les noves
						versions. Per desar els canvis dóna-li a "ok".
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">4 - Language</h1>
					<img src="/images/AP14-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat de language podem seleccionar l'idioma que volem que es mostri el programa, tan sols selecciona l'idioma que vols
						que es mostri el programa i doni a "ok" per desar-lo.
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">5 - Display</h1>
					<img src="/images/AP15-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat de display podem canviar la resolució del programa i també la mida de les lletres. Per desar els canvis només
						doneu a "ok".
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">6 - Proxy</h1>
					<img src="/images/AP16-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						A l'apartat de proxy podem canviar si volem utilitzar proxy amb ajustaments automàtics, si volem fer servir internet o si
						volem fer servir un proxy personalitzada, si vols guardar els canvis dóna-li a "ok".
					</h1>
					<h1 class="mt-2 text-base font-semibold text-blue-300 underline lg:text-xl">7 - Interface</h1>
					<img src="/images/AP17-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I per últim a l'apartat interface podem canviar el tema del programa (Clar, Fosc o segons el nostre sistema). Un cop canviat
						dóna-li a "ok" per desar els canvis.
					</h1>
					<h1 class="mt-8 text-base font-semibold text-pink-300 underline lg:text-xl">Configuració de l'administrador de medis virtuals</h1>
					<img src="/images/AP18-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Aquí quan comencem a tenir màquines virtuals doncs aquí podrem administrar els nostres discos virtuals. En aquesta pestanya
						que se'ns obre podem afegir un disc, crear, eliminar, copiar, moure, alliberar, cercar o veure'n les propietats.
					</h1>
					<img src="/images/AP19-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-8 text-base font-semibold text-purple-300 underline lg:text-xl">Configuració de l'administració de la xarxa</h1>
					<img src="/images/AP20-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Aquí podem administrar les nostres xarxes del host/NAT/cloud, podem afegir, eliminar o mirar les propietats de la xarxa.
					</h1>
					<img src="/images/AP21-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-8 text-base font-semibold text-yellow-300 underline lg:text-xl">Procés d'instal·lació d'extensión Pack</h1>
					<img src="/images/AP22-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Primer necessitem anar a la pàgina del principi on ens instal·lem VirtualBox per instal·lar l'Extension Pack, aquí et deixo la
						pàgina una altra vegada:
					</h1>
					<div>
						<a
							href="https://www.virtualbox.org/wiki/Downloads"
							target="_blank"
							class="group mb-2 mr-2 mt-2 inline-flex items-center justify-center overflow-hidden rounded-lg bg-gradient-to-br from-purple-600 to-blue-500 p-0.5 text-center text-sm font-medium text-gray-900 hover:text-white focus:outline-none focus:ring-4 focus:ring-blue-300 group-hover:from-purple-600 group-hover:to-blue-500 dark:text-white dark:focus:ring-blue-800"
						>
							<svg
								xmlns="http://www.w3.org/2000/svg"
								fill="none"
								viewBox="0 0 24 24"
								stroke-width="1.5"
								stroke="currentColor"
								class="mx-2 h-6 w-6 transition-all duration-75 ease-in group-hover:bg-opacity-0"
							>
								<path
									stroke-linecap="round"
									stroke-linejoin="round"
									d="M3 16.5v2.25A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75V16.5M16.5 12L12 16.5m0 0L7.5 12m4.5 4.5V3"
								/>
							</svg>

							<span
								class="rounded-md bg-white px-5 py-2.5 transition-all duration-75 ease-in group-hover:bg-opacity-0 dark:bg-gray-900"
							>
								Descarregar
							</span>
						</a>
					</div>
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop a la pàgina hem de cercar l'apartat de "VirtualBox 7.0.10 Oracle VM VirtualBox Extension Pack" i donar-li a "All
						supported platforms" per començar la descàrrega de l'extension pack.
					</h1>
					<img src="/images/AP23-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop instal·lat el fitxer, hem d'anar al nostre VirtualBox i donar-li a la icona que posa "Install", seleccionem l'arxiu que
						hem descarregat anomenat "Oracle_VM_VirtualBox_Extension_Pack-7.0.10.vbox-extpack" i us donem a obrir, ens posarà una finestra
						dient que si de veritat ho instal·larem, li donem a "Install", després baixem fins a baix dels termes i condicions i li donem
						a "I agree" i ja tindríem l'Extension Pack instal·lat al nostre VirtualBox.
					</h1>
					<img src="/images/AP24-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP25-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP26-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP27-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP28-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim l'extension pack instal·lat tenim aquestes noves funcions al nostre VirtualBox; Suport per a dispositius USB
						2.0 i USB 3.0, Passat de la càmera web de l'allotjament, Protocol d'escriptori remot de VirtualBox (VRDP), Xifratge d'imatges
						de disc amb algorisme AES i ROM d'arrencada Intel PXE.
					</h1>
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
				<div id="configuració del virtualbox">
					<div class="w-full">
						<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
							3 - Conclusió
							<hr class="my-2 h-1 w-full rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
						</h1>
					</div>
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Ara ja tindríem el nostre VirtualBox ben configurat i llest per simular màquines virtualment.
					</h1>
					<img src="/images/AP29-sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
				</div>
			</div>
		</div>
	</div>
</template>
