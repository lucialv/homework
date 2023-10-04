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
					<h1 class="text-lg font-bold text-white lg:text-2xl">AP_05_Instal·lació de Android</h1>
				</div>
				<hr class="mt-2 h-1 rounded border-0 bg-gradient-to-br from-white to-pink-500 md:w-[700px]" />
				<div id="instalacio-de-virtualbox">
					<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						1 - Instalació de la ISO de Android
					</h1>
					<hr class="my-2 h-1 rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Primer hem d'anar a la pàgina de Android per descarregar l'ISO, per això donar-li aquest botó per anar directament a la pàgina
						web de la descàrrega.
					</h1>
					<div>
						<a
							href="https://Androidproject.org/es/workstation/download/"
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
					<img src="/images/AP01-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja estem a la pàgina d'instal·lació donar-li al botó de descarregar, això començarà la descarrega del ISO.
					</h1>
					<img src="/images/AP02-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim la ISO instal·lada, ens dirigim al VirtualBox i donem a "New".
					</h1>
					<img src="/images/AP03-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Se'ns obrirà aquesta pestanya:"</h1>
					<img src="/images/AP05-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Posem de nom a la màquina "Android" i seleccionem l'iso que acabem de descarregar. A la versió posem Ubuntu 64 Bits, és
						important per l'instal·lació. I donem a "Next"
					</h1>
					<img src="/images/AP03-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà quanta RAM i quants processadors li posarem a aquesta màquina, segons diu la pàgina de Android, amb 4GB de
						RAM i 2 processador ja vas bé. Una vegada acabat de possar tot el que volem li donem a "Next"
					</h1>
					<img src="/images/AP04-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quant d'espai donarem a la màquina, a la pàgin de Android posa uns 10GB. Un cop posats li donem a "Next"
					</h1>
					<img src="/images/AP05-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens surt una pestanya de confirmació on surt com es crearà la màquina virtual, si estem d'acord donem a "Finish".
					</h1>
					<img src="/images/AP06-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ja tindriem la nostra màquina virtual afegida al VirtualBox, però falta instal·lar-la, per això encendrem la màquina
						donant-li dos clics.
					</h1>
					<img src="/images/AP07-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						<!-- Ara ens pregunta quin idioma volem per a la instal·lació i també serà l'idioma de l'OS, seleccionem el que més ens agradi, en
						el meu cas posaré espanyol i li donem a Instalar Android. -->
						Li donarem a "Installation - Install Android-x86 to hard disk".
					</h1>
					<img src="/images/AP08-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara seleccionarem "Create/Modify partitions".</h1>
					<img src="/images/AP09-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Li donarem que no.</h1>
					<img src="/images/AP10-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara necessitem donar-li al botó de "New", una vegada donat, ens preguntarà si volem que la partició sigui lògica o primària,
						li donem a primària. Posem l'espai del nostre disc a MB (o li donem a enter) I així ens quedaria el resultat:
					</h1>
					<img src="/images/AP11-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara donem a "Bootable"</h1>
					<img src="/images/AP12-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I donem a "Write" i posem "Yes" per confirmar.</h1>
					<img src="/images/AP13-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara seleccionem la partició que acabem de crear i donem a "ok".
					</h1>
					<img src="/images/AP14-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara seleccionem ext4 que és el tipus de fitxers de Linux i Android és un tipus de Linux. I donem a "Ok".
					</h1>
					<img src="/images/AP15-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ara li donem a "Yes" per confirmar.</h1>
					<img src="/images/AP16-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Li donem a "yes" una altre vegada y comenzará a instalarse.</h1>
					<img src="/images/AP17-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop acaba la instal·lació ens diu que volem fer, donem a "Run Android-x86" i donem a "ok".
					</h1>
					<img src="/images/AP18-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quin idioma volem, seleccionem el que més ens agradi, en el meu cas posaré espanyol i li donem a començar.
					</h1>
					<img src="/images/AP19-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Ahora ens pregunta si volem conectar wifi, li donem a saltar.</h1>
					<img src="/images/AP20-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ahora ens pregunta si la data i l'hora estàn bé, li donem a seguent.
					</h1>
					<img src="/images/AP21-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ens pregunta si volem donar permisos per a la ubicació i que accedeixin a les nostres dades, jo li he donat que no, però tu
						pots posar el que vulguis. Donem a aceptar.
					</h1>
					<img src="/images/AP22-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens demana una contrasenya per accedir al sistema, si vols posar una contrasenya selecciona la que creguis convenient, si
						no, com és el meu cas, dónes ara no.
					</h1>
					<img src="/images/AP23-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ja tindriem el nostre sistema operatiu de Android funcionant perfectament! (No té Guest Addition)
					</h1>
					<img src="/images/AP24-5sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />

					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
			</div>
		</div>
	</div>
</template>
