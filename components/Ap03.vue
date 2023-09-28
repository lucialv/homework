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
					<h1 class="text-lg font-bold text-white lg:text-2xl">AP_03_Instal·lació d'Ubuntu</h1>
				</div>
				<hr class="mt-2 h-1 rounded border-0 bg-gradient-to-br from-white to-pink-500 md:w-[700px]" />
				<div id="instalacio-de-virtualbox">
					<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						1 - Instalació de la ISO de Ubuntu
					</h1>
					<hr class="my-2 h-1 rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Primer hem d'anar a la pàgina de Ubuntu per descarregar l'ISO, per això donar-li aquest botó per anar directament a la pàgina
						web de la descàrrega.
					</h1>
					<div>
						<a
							href="https://ubuntu.com/download/desktop"
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
					<img src="/images/AP01-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja estem a la pàgina d'instal·lació donar-li a descarregar la versió Ubuntu 22.04.3 LTS, això començarà la descarrega
						del ISO.
					</h1>
					<img src="/images/AP02-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim la ISO instal·lada, ens dirigim al VirtualBox i donem a "New".
					</h1>
					<img src="/images/AP03-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Se'ns obrirà aquesta pestanya:"</h1>
					<img src="/images/AP05-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Posem de nom a la màquina "Ubuntu", seleccionem l'iso que acabem de descarregar i finalment marquem l'opció de "Skip
						Unattended Installation" per fer una bona instal·lació. I donem a "Next"
					</h1>
					<img src="/images/AP04-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà quanta RAM i quants processadors li posarem a aquesta màquina, segons diu la pàgina de Ubuntu, amb 4GB de
						RAM i 2 processador ja vas bé. Una vegada acabat de possar tot el que volem li donem a "Next"
					</h1>
					<img src="/images/AP05-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quant d'espai donarem a la màquina, a Ubuntu amb 25GB està bé però posarem 30GB per si de cas. Un cop posats
						li donem a "Next"
					</h1>
					<img src="/images/AP06-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens surt una pestanya de confirmació on surt com es crearà la màquina virtual, si estem d'acord donem a "Finish".
					</h1>
					<img src="/images/AP07-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ja tindriem la nostra màquina virtual afegida al VirtualBox, però falta instal·lar-la, per això encendrem la màquina
						donant-li dos clics.
					</h1>
					<img src="/images/AP08-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quin idioma volem per a la instal·lació i també serà l'idioma de l'OS, seleccionem el que més ens agradi, en
						el meu cas posaré espanyol i li donem a Instalar Ubuntu.
					</h1>
					<img src="/images/AP10-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens pregunta quina distribució del teclat volem, donem a la que ens vagi millor i donem a Continuar.
					</h1>
					<img src="/images/AP11-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quin tipus d'instal·lació volem a una instal·lació normal i deixem les altres opcions com vulguem, un cop
						acabat li donem a continuar.
					</h1>
					<img src="/images/AP12-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens diu que si volem esborrar el nostre disc i instal·lar Ubuntu, li donem a Instal·lar ara.
					</h1>
					<img src="/images/AP13-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Confirmem.</h1>
					<img src="/images/AP14-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I li posem on vivim.</h1>
					<img src="/images/AP15-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ara ens pregunta el nostre nom, el nom que posarem a l'equip, el nom d'usuari i la contrasenya. Un cop emplenat li donem a
						continuar.
					</h1>
					<img src="/images/AP17-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I es començara a instal·lar.</h1>
					<img src="/images/AP18-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Quan s'acabi la descàrrega ens posarà que s'ha instal·lat i que cal reiniciar, així que us donem a reiniciar ara.
					</h1>
					<img src="/images/AP19-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I en obrir-vos seleccionem el nostre nom d'usuari, poso la contrasenya i se'ns obrirà l'escriptori.
					</h1>
					<img src="/images/AP20-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens demana que connectem un compte si vols, jo li donaré ometre.
					</h1>
					<img src="/images/AP21-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem tenir Ubuntu Pro, li donem a ometre i continuar.
					</h1>
					<img src="/images/AP22-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem enviar estadistiques als desenvolupadors per millorar Ubuntu, cal pensar que és codi obert i darrere
						d'això només hi ha desenvolupadors independents, li donem que sí si vols col·laborar i si no doncs dónes que no.
					</h1>
					<img src="/images/AP23-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens demana si volem activar la ubicacio, seleccionem el que volem i li donem a següent.
					</h1>
					<img src="/images/AP25-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I per últim ens diu si volem instal·lar alguna aplicació, li donem a fet i ja tindríem Ubuntu per utilitzar lliurement.
					</h1>
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
				<div id="guest edition">
					<div class="w-full">
						<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
							Instalació del Guest Addition
							<hr class="my-2 h-1 w-full rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
						</h1>
					</div>
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Per instal·lar el Guest Addition hauríem d'anar a "Devices" i donar-li a l'opció de "Insert Guest Addition CD Image..."
					</h1>
					<img src="/images/AP26-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">Li donem al disc que ha aparegut a l'esquerra.</h1>
					<img src="/images/AP27-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Li donem a "VBox_GAs(la teva versió)" i ens sortirà una pestanya que ens diu que si volem executar el programari per
						instal·lar el Guest Addition, li donem a executar.
					</h1>
					<img src="/images/AP28-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Un cop acabada la descàrrega ja tindríem el nostre Ubuntu instal·lat amb Guest Addition i llest per fer el que vulguem amb
						ell.
					</h1>
					<img src="/images/AP29-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
			</div>
		</div>
	</div>
</template>
