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
					<h1 class="text-lg font-bold text-white lg:text-2xl">AP_02_Instal·lació d'Ubuntu</h1>
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
							href="https://www.Ubuntu.org/CD/http-ftp/"
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
					<img src="/images/AP01-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja estem a la pàgina d'instal·lació hem d'escollir la nostra instal·lació preferida. (La més comuna es la amd64)
					</h1>
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens enviarà a una altra pàgina, baixem fins a baix de la pàgina i seleccionem el fitxer .iso per començar la descàrrega.
					</h1>
					<img src="/images/AP03-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim la ISO instal·lada, ens dirigim al VirtualBox i donem a "New".
					</h1>
					<img src="/images/AP04-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Se'ns obrirà aquesta pestanya:"</h1>
					<img src="/images/AP05-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Posem de nom a la màquina "Ubuntu", seleccionem l'iso que acabem de descarregar i finalment marquem l'opció de "Skip
						Unattended Installation" per fer una bona instal·lació.
					</h1>
					<img src="/images/AP06-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I donem a "Next"</h1>
					<img src="/images/AP07-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà quanta RAM i quants processadors li posarem a aquesta màquina, segons diu la pàgina de Ubuntu, amb 1GB de
						RAM i 1 processador ja vas bé, però posaré 4GB de RAM i 2 processadors perquè vagi tot millor. Una vegada acabat de possar tot
						el que volem li donem a "Next"
					</h1>
					<img src="/images/AP08-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quant d'espai donarem a la màquina, a Ubuntu amb 25GB està bé però posarem 30GB per si de cas. Un cop posats
						li donem a "Next"
					</h1>
					<img src="/images/AP09-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens surt una pestanya de confirmació on surt com es crearà la màquina virtual, si estem d'acord donem a "Finish".
					</h1>
					<img src="/images/AP10-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ja tindriem la nostra màquina virtual afegida al VirtualBox, però falta instal·lar-la, per això encendrem la màquina
						donant-li dos clics.
					</h1>
					<img src="/images/AP11-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que se'ns ha obert la màquina el primer és que ens surt és que hem d'instal·lar Ubuntu, per això li donarem a Install
						(Usant les fletxes per moure's i Enter per acceptar)
					</h1>
					<img src="/images/AP12-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quin idioma volem per a la instal·lació i també serà l'idioma de l'OS, seleccionem el que més ens agradi, en
						el meu cas posaré espanyol i li donem a Enter.
					</h1>
					<img src="/images/AP13-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens pregunta quina ubicació és la nostra per posar lhora del sistema i coses diverses. Seleccionem d'on som i donem a Enter.
					</h1>
					<img src="/images/AP14-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens pregunta quina distribució del teclat volem, donem a la que ens vagi millor i donem a Enter.
					</h1>
					<img src="/images/AP15-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara comença a instal·lar-se el Ubuntu.</h1>
					<img src="/images/AP16-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop acabada la instal·lació ens pregunta quin nom volem posar a la Màquina, en el meu cas li posaré el meu nom, però tu
						pots posar el que vulguis. Un cop posat li donem a "Continuar".
					</h1>
					<img src="/images/AP17-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà un nom del domini, si en tenim posem un si voleu però en el meu cas el deixaré en blanc i el donaré a
						continuar.
					</h1>
					<img src="/images/AP18-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quina contrasenya li posem per a l'usuari administrador (root), posem una contrasenya si volem o si no ho
						deixem en blanc i donem a "Continuar".
					</h1>
					<img src="/images/AP19-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						En el cas que hàgim posat contrasenya ens la demanarà posar-la una altra vegada, la posem i us donem a "Continuar".
					</h1>
					<img src="/images/AP20-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens demana que introduïm el nom d'usuari per a l'usuari que no té permisos d'administrador, un cop posat us donem a
						"Continuar".
					</h1>
					<img src="/images/AP21-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens demana la contrasenya de l'usuari, posem la que vulguem i donem a "Continuar".
					</h1>
					<img src="/images/AP22-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">La introduïm una altre vegada.</h1>
					<img src="/images/AP23-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Posem la nostra zona horaria i li donem a Enter.</h1>
					<img src="/images/AP24-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta com volem fer les particions, com no sabem, li donem a la primera opció (Si saps pots fer-les manualment).
					</h1>
					<img src="/images/AP25-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Seleccionem el nostre disc dur i li donem a Enter.</h1>
					<img src="/images/AP26-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un altre cop li donem a la primera perquè no sabem com va això de les particions, si vols pots seleccionar les altres si saps
						com va.
					</h1>
					<img src="/images/AP27-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens posa com es crearan les particions i si estem segurs li donem a "Finalitzar".
					</h1>
					<img src="/images/AP28-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ens torna a preguntar si estem segurs, donem que si.</h1>
					<img src="/images/AP29-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara haurem d'esperar que la instal·lació acabi.</h1>
					<img src="/images/AP30-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem instal·lar paquets addicionals, com volem fer una instal·lació mínima en aquest cas li donaré que no
						però si tu vols instal·lar més coses ho pots fer.
					</h1>
					<img src="/images/AP31-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem instal·lar els paquets mitjançant internet, una altre vegada li donarem a que no.
					</h1>
					<img src="/images/AP32-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Esperem que s'instal·lin els programes.</h1>
					<img src="/images/AP33-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem enviar estadistiques als desenvolupadors per millorar Ubuntu, cal pensar que és codi obert i darrere
						d'això només hi ha desenvolupadors independents, li donem que sí si vols col·laborar i si no doncs dónes que no.
					</h1>
					<img src="/images/AP34-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta que entern volem Ubuntu, la més famosa és el GNOME així que seleccionaré aquesta però pots seleccionar la que
						vulguis.
					</h1>
					<img src="/images/AP35-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I esperem a que s'acabi la descàrrega.</h1>
					<img src="/images/AP36-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem instal·lar GRUB per quan arrenquem la màquina, li donem que sí.
					</h1>
					<img src="/images/AP37-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Seleccionem el nostre disc dur.</h1>
					<img src="/images/AP38-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I esperem a que s'acabi la descàrrega.</h1>
					<img src="/images/AP39-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I per fi s'ha completat la descàrrega, li donem a continuar per reiniciar el sistema.
					</h1>
					<img src="/images/AP40-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop reiniciada la màquina ja tindríem el sistema de Ubuntu llest per utilitzar, seleccionem el nostre usuari i posem la
						contrasenya i entraríem al sistema.
					</h1>
					<img src="/images/AP41-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop obert per primer cop, ens demanarà seleccionar l'idioma, li posem el nostre idioma favorit i us donem a següent.
					</h1>
					<img src="/images/AP42-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Li posem la nostra distribució de teclat.</h1>
					<img src="/images/AP43-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens demana si volem activar la ubicacio, seleccionem el que volem i li donem a següent.
					</h1>
					<img src="/images/AP44-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta si volem posar un compte, en el meu cas us donaré a ometre perquè no vull posar cap compte.
					</h1>
					<img src="/images/AP45-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I ja tindríem instal·lat Ubuntu.</h1>
					<img src="/images/AP46-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
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
					<img src="/images/AP47-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">Obrim l'explorador d'arxius.</h1>
					<img src="/images/AP48-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Li donem a "VBox_GAs(la teva versió)" i ens sortirà una pestanya que ens diu que si volem executar el programari per
						instal·lar el Guest Addition, li donem a executar.
					</h1>
					<img src="/images/AP49-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<img src="/images/AP50-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Ens demanarà la contrasenya de l'administrador, la posem i li donem a autenticar.
					</h1>
					<img src="/images/AP51-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">Esperem a que s'instal·li.</h1>
					<img src="/images/AP52-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Un cop acabada la descàrrega ja tindríem el nostre Ubuntu instal·lat amb Guest Addition i llest per fer el que vulguem amb
						ell.
					</h1>
					<img src="/images/AP53-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
			</div>
		</div>
	</div>
</template>
