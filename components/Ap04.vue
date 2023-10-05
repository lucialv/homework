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
					<h1 class="text-lg font-bold text-white lg:text-2xl">AP_04_Instal·lació de Fedora</h1>
				</div>
				<hr class="mt-2 h-1 rounded border-0 bg-gradient-to-br from-white to-pink-500 md:w-[700px]" />
				<div id="instalacio-de-virtualbox">
					<h1 class="mt-6 bg-gradient-to-r from-sky-300 to-blue-500 bg-clip-text text-lg font-bold text-transparent lg:text-2xl">
						1 - Instalació de la ISO de Fedora
					</h1>
					<hr class="my-2 h-1 rounded border-0 bg-gradient-to-br from-sky-300 to-blue-500" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Primer hem d'anar a la pàgina de Fedora per descarregar l'ISO, per això donar-li aquest botó per anar directament a la pàgina
						web de la descàrrega.
					</h1>
					<div>
						<a
							href="https://fedoraproject.org/es/workstation/download/"
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
					<img src="/images/AP01-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja estem a la pàgina d'instal·lació donar-li al botó de descarregar (foto anterior) , això començarà la descarrega del
						ISO.
					</h1>
					<img src="/images/AP02-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara que ja tenim la ISO instal·lada, ens dirigim al VirtualBox i donem a "New".
					</h1>
					<img src="/images/AP03-3sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Se'ns obrirà aquesta pestanya:"</h1>
					<img src="/images/AP05-2sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Posem de nom a la màquina "Fedora" i seleccionem l'iso que acabem de descarregar. I donem a "Next"
					</h1>
					<img src="/images/AP03-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens preguntarà quanta RAM i quants processadors li posarem a aquesta màquina, segons diu la pàgina de Fedora, amb 4GB de
						RAM i 2 processador ja vas bé. Una vegada acabat de possar tot el que volem li donem a "Next"
					</h1>
					<img src="/images/AP04-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quant d'espai donarem a la màquina, a la pàgin de Fedora posa uns 40GB. Un cop posats li donem a "Next"
					</h1>
					<img src="/images/AP05-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens surt una pestanya de confirmació on surt com es crearà la màquina virtual, si estem d'acord donem a "Finish".
					</h1>
					<img src="/images/AP06-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						I ja tindriem la nostra màquina virtual afegida al VirtualBox, però falta instal·lar-la, per això encendrem la màquina
						donant-li dos clics.
					</h1>
					<img src="/images/AP08-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						<!-- Ara ens pregunta quin idioma volem per a la instal·lació i també serà l'idioma de l'OS, seleccionem el que més ens agradi, en
						el meu cas posaré espanyol i li donem a Instalar Fedora. -->
						Li donarem a "Start Fedora-Workstation-Live 38" per iniciar Fedora.
					</h1>
					<img src="/images/AP09-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Li donarem a "Install Fedora" per començar l'instal·lació de Fedora.
					</h1>
					<img src="/images/AP10-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens pregunta quin idioma volem per a la instal·lació i també serà l'idioma de l'OS, seleccionem el que més ens agradi, en
						el meu cas posaré espanyol i li donem a Continuar.
					</h1>
					<img src="/images/AP11-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Ara ens diu quina serà la nostra distribució del teclat i quina serà la zona horària del temps. També ens posa que seleccionem
						el nostre disc on instal·larem fedora, per això cliquem i seleccionem el disc que vulguem, quan el seleccions li dónes a fet i
						per últim li donem a Començar la instal·lació.
					</h1>
					<img src="/images/AP12-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">Esperem a que s'instali</h1>
					<img src="/images/AP13-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">
						Un cop finalitzada l'instal·lació li donem a finalitzar l'instalació i es reiniciarà.
					</h1>
					<img src="/images/AP14-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="mt-2 text-base font-semibold text-white lg:text-xl">I ja tindriem Fedora instal·lat i llest per utilitzar.</h1>
					<img src="/images/AP15-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
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
					<img src="/images/AP16-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">Esperem a que s'instali.</h1>
					<img src="/images/AP17-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<h1 class="text-base font-semibold text-white lg:text-xl">
						Un cop acabada la descàrrega ja tindríem el nostre Fedora instal·lat amb Guest Addition i llest per fer el que vulguem amb
						ell.
					</h1>
					<img src="/images/AP19-4sistema.png" alt="foto" class="mx-auto mt-4 w-[200px] rounded-md md:w-[600px]" />
					<hr class="mx-auto my-32 h-1 w-48 rounded border-0 dark:bg-gray-500" />
				</div>
			</div>
		</div>
	</div>
</template>
