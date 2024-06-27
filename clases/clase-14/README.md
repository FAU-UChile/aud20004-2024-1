# clase-14

jueves 27 junio 2024

repaso unidades 7(luz) y 8 (electricidad)

## luz

## espectro de luz visible

como humanos, vemos ondas cuyas longitudes de onda van entre aproximadamente 400 y 800 nanómetros.

$$1 \cdot nanómetro = 1 \cdot nm = 1 \cdot 10^{-9} \cdot m$$

los colores del espectro visible, ordenadas de longitud de onda más corta a más larga:

| color    | longitud de onda (nm) | frecuencia (THz) |
| :------- | :-------------------- | :--------------- |
| violeta  | 380-450               | 670-790          |
| azul     | 450-485               | 620-670          |
| cyan     | 485-500               | 600-620          |
| verde    | 500-565               | 530-600          |
| amarillo | 565-590               | 510-530          |
| naranja  | 590-625               | 480-510          |
| rojo     | 625-750               | 400-480          |

a cada rango de longitud de onda, podemos encontrar la frecuencia asociada, que es cómodo medir en Tera Hertz.

$$1 \cdot THz = 1 \cdot 10^{12} \cdot Hz$$

ondas de menor frecuencia que el espectro visible son infrarrojas, ondas de mayor frecuencia que el espectro visible son llamadas ultravioleta.

## velocidad de la luz

$$c = 3 \cdot 10^8 \cdot \frac{m}{s}$$

es la máxima velocidad posible.

esto lleva al concepto de año luz, que es una unidad de distancia, que simboliza cuánta distancia es capaz de recorrer la luz en un año.

$$1 \cdot añoluz = velocidad_{luz} * 1 \cdot año = 3 \cdot 10^{8} \frac{m}{s} \cdot 365.25 \cdot 24 \cdot 60 \cdot 60 s = (3 \cdot 365 \cdot 24 \cdot 60 \cdot 60) \cdot 10^{8} m = (3 \cdot 365 \cdot 24 \cdot 36) \cdot 10^{10} \cdot m =  \cdot 10^{10} \cdot m = 9.46728 \cdot 10^{15} \cdot m \approx 10^{16} \cdot m$$

## percepción de color

se estima que un humano puede distinguir hasta 10 millones de colores, eso lleva a que a nivel computacional se usen 24 bits, lo que resulta alrededor de 16 millones de colores.

de esos 24 bits, 8 se usan por cada canal rojo, verde y azul.

si usamos 8 bits para cada color, tenemos 24 bits en total, o sea, 2^24 posibilidades.

$$2^{24} = 16,777,216$$

## colores y computadores

un pixel RGB es capaz de brillar y con eso generar color.

si tenemos B bits de resolución por canal de color, entonces un pixel tiene 3B bits para representar su color.

entonces la cantidad de colores posibles en 1 pixel es:

$$colores_{pixel}= 2^{3 \cdot B}$$

si tenemos una pantalla de resolución 1080p, con 1920 por 1080 pixeles, entonces tenemos un total de.

$$pixeles = 1920 \cdot 1080 = 2,073,600$$

y cada uno de esos pixeles, puede ser de un color distinto, y necesitamos 3\*B bits de información para cada uno, y así definir su color.

si tenemos una tasa de refresco de 60 Hz, significa que tenemos 60 cuadros por segundo.

## fuerza eléctrica

la ecuación de fuerza eléctrica entre 2 cargas viene dada por:

$$F_{electrica} = K \cdot \frac{q_1 \cdot q_2}{r^2}$$

donde:

- K es la constante de Coulomb
- $q_1$ y $q_2$ son cargas eléctricas, que tienen signo
- r es la distancia entre las cargas

la constante K de Coulomb tiene el siguiente valor y unidades:

$$K \approx 9 \cdot 10^9 \cdot \frac{N \cdot m^2}{C^2}$$

## corriente eléctrica

la corriente eléctrica la denotamos por I, de intensidad, y se mide en Amperes (A), que es una representación de carga eléctrica por unidad de tiempo. la unidad de carga eléctrica es Coulomb, con lo que 1 Ampere es igual a 1 Coulomb por segundo.

$$1 \cdot A = 1 \cdot \frac{C}{s}$$

1 electrón posee una pequeña carga, de aproximadamente

$$1 \cdot electron \approx 1.6 \cdot 10^{-19} \cdot  C$$

lo que significa que 1 Ampere es muchísima carga por segundo, muchísimos electrones.

## voltaje eléctrico

el voltaje eléctrico es una medida de potencial eléctrico, y se mide en volts, donde 1 volt (V) es equivalente a 1 Joule dividido por Coulomb.

$$1 \cdot V = 1 \frac{J}{C}$$

las fuentes de poder que usamos en la vida cotidiana, como el enchufe, una batería, un puerto USB, tienen una medida de voltaje y una medida de corriente, donde ocurre lo siguiente:

- el voltaje entregado es IGUAL al de la especificación. ejemplos: enchufe 220 V en Chile, puerto USB 5 V, batería 1.5 V o 9V o algún otro estándar.
- la corriente entregada está LIMITADA por el valor de la especificación. si una fuente de poder es de 10 A, significa que lo máximo que provee es 10 A.

## potencia eléctrica

la potencia eléctrica se mide en watts (W), y un Watt es la cantidad de energía por segundo.

$$1 \cdot W = 1 \cdot {J}{s}$$

la relación entre potencia, voltaje y corriente viene dada por la ecuación:

$$P = V \cdot I$$

y si analizamos las unidades, podemos comprobar:

$$1 \cdot W = 1 \cdot V \cdot 1 \cdot A = 1 \cdot \frac{J}{C} \cdot \frac{C}{s} = 1 \cdot {J}{s}$$

evaluación: control 4, unidades 7, 8
