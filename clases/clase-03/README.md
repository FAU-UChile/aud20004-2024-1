# clase-03

jueves 28 marzo 2024

## repaso

ecuaciones importantes:

$$\vec{F} = m \cdot \vec{a}$$

$$F_{G} = \frac{G \cdot m_{1} \cdot m_{2}}{r^{2}}$$

$$x(t) = x_0 + v_o \cdot t + \frac{1}{2} a \cdot t^{2}$$

$$v(t) = v_0 + a \cdot t$$

## control-01

jueves 28 marzo 2023, presencial

instrucciones:

- control individual
- entregar soluciones en hojas con nombre, fecha, número de ejercicio
- responder máximo 3 de los 4 ejercicios
- evaluaremos los 2 mejores ejercicios que contesten, el tercero no cuenta

pauta:

- cada control tiene 1 punto base, más 3 puntos por cada ejercicio considerado
- cada ejercicio tiene parte a) y b), cada una de 1.5 puntos máximo donde:
  - 1.5 puntos si el proceso está completo, y el resultado es correcto
  - 1.0 puntos si el proceso está completo, pero el resultado tiene errores menores
  - 0.5 puntos si el proceso empezó bien, pero luego hubo errores graves y resultado incorrecto
  - 0.0 puntos si está en blanco o el resultado y el proceso tienen errores gravísimos

## consejos

- usa calculadora y los apuntes del curso
- no olvides las unidades de medida
- $1[N] = 1[kg\frac{m}{s^2}]$
- $G = 6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right]$

## ejercicio-01 (3 puntos)

un vehículo de $300[kg]$ de masa se mueve en línea recta a $30[km/h]$. sorpresivamente se encuentra con un peatón y debe frenar brúscamente.

a) ¿Qué aceleración promedio deben aplicar los frenos para detenerlo en 2 segundos?

solución:

$a = \frac{\Delta v}{\Delta t}$

$a = \frac{v_{f} - v_{i}}{t_{f} - t_{i}}$

$a = \frac{0 \frac{m}{s} - 30 \frac{km}{hora}}{2 s - 0  s}$

$a = \frac{- 30 \frac{1000 m}{3600 s}}{2 s}$

$a = \frac{- 150}{36} \frac{m}{s^{2}}$

$a = \frac{- 25}{6} \frac{m}{s^{2}}$

$a \approx -4.2 \frac{m}{s^{2}}$

b) ¿Cuántos metros recorre mientras está frenando?

solución:

$x(t) = x_{0} + v_{0} \cdot t + \frac{1}{2} \cdot a \cdot t^{2}$

$x(t=2s) = 0m + 30 \frac{km}{hora} \cdot (2 s) + \frac{1}{2} \cdot \frac{- 25}{6} \frac{m}{s^{2}} \cdot (2s)^{2}$

$x(t=2s) = 60 \frac{1000m}{3600s} \cdot s + \frac{1}{2} \cdot \frac{- 25}{6} \frac{m}{s^{2}} \cdot 4 s^{2}$

$x(t=2s) = 60 \frac{10m}{36} - 2 \cdot \frac{25}{6}m$

$x(t=2s) = \frac{100}{6}m - \frac{50}{6}m$

$x(t=2s) = \frac{50}{6}m$

$x(t=2s) = \frac{25m}{3}$

$x(t=2s) \approx 8.3 m$

## ejercicio-02 (3 puntos)

un grupo de tres atletas se prepara para una carrera de relevos de 3 x 100 metros.

su entrenador ha logrado medir la aceleración promedio que alcanza cada atleta en sus carreras:

| atleta | aceleración promedio |
| ------ | -------------------- |
| 1      | $0.81 [m/s^2]$       |
| 2      | $0.72 [m/s^2]$       |
| 3      | $0.83 [m/s^2]$       |

a) si cada atleta debe recorrer $100[m]$ planos, cuál será el tiempo total esperado de la carrera? asume que cada atleta parte con una velocidad inicial de $0[m/s]$.

solución:

$x(t) = x_{0} + v_{0} \cdot t + \frac{1}{2} \cdot a \cdot t^{2}$

para atleta 1, despejamos el tiempo $t_1$ cuando $x_1(t_1) = 100[m]$

$x_1(t_1) = 0 m + 0 \frac{m}{s} \cdot t_1 + \frac{1}{2} \cdot 0.81 \frac{m}{s^2} \cdot {t_1}^{2}$

y como $x_1(t_1) = 100[m]$ resulta:

$100 m = \frac{1}{2} \cdot 0.81 \frac{m}{s^2} \cdot {t_1}^{2}$

multiplicando a ambos lados por 2:

$200 m = 0.81 \frac{m}{s^2} \cdot {t_1}^{2}$

despejando $t_1$:

${t_1}^2 = \frac{200 m}{0.81 \frac{m}{s^2}}$

${t_1}^2 = \frac{200 s^2}{0.81}$

y aplicando raíz cuadrada:

${t_1} = \sqrt{\frac{200 s^2}{0.81}}$

${t_1} = \sqrt{\frac{200 s^2}{0.81}}$

${t_1} \approx 15.7 s$

para el atleta 2, despejamos el tiempo $t_2$ cuando $x_2(t_2) = 100[m]$

$100 m = \frac{1}{2} \cdot 0.72 \frac{m}{s^2} \cdot {t_2}^{2}$

y despejando $t_2$:

${t_2}^{2} = \frac{200}{0.72} s^2$

${t_2} \approx 16.6 s$

y lo mismo para el atleta 3 resulta en:

${t_3}^{2} = \frac{200}{0.83} s^2$

$t_3  \approx 15.52 s$

b) qué velocidad experimenta el atleta N°3 al momento de llegar a la meta?

solución:

usamos la ecuación de velocidad:

$v(t_3) = v_0 + a_3 \cdot t_3$

y reemplazando los datos:

$v(t_3) \approx 0 \frac{m}{s} + 0.83 \frac{m}{s^2} \cdot 15.52 s$

y simplificando:

$v(t_3) \approx 12.88 \frac{m}{s}$

## ejercicio-03 (3 puntos)

a) calcule aproximadamente la fuerza gravitacional entre la tierra y marte sabiendo que:

- distancia entre la tierra y marte = $3.15 \cdot 10^{8} \ [km]$
- masa de la tierra = $5.97 \cdot 10^{24} \ [kg]$
- masa de marte = $6.42 \cdot 10^{23} \ [kg]$

solución:

por definición, la fuerza gravitacional entre dos cuerpos es:

$$F_{G} = G \frac{m_1 \cdot m_2}{r^2}$$

reemplazando los valores:

$$F_{G} = 6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right] \frac{5.97 \cdot 10^{24} kg \cdot 6.42 \cdot 10^{23} kg}{(3.15 \cdot 10^{8} \ km)^2}$$

simplificando los kg:

$$F_{G} = 6.67 \cdot 10^{-11} \left[Nm^2\right] \frac{5.97 \cdot 10^{24} \cdot 6.42 \cdot 10^{23}}{(3.15 \cdot 10^{8} \ km)^2}$$

agrupando números, luego potencias de 10 y luego unidades:

$$F_{G} = \frac{6.67 \cdot 5.97 \cdot 6.42}{3.15^2}   \frac{ 10^{-11} \cdot 10^{24} \cdot 10^{23}}{ 10^{16} } \cdot \frac{Nm^2}{(km)^2}$$

simplificando:

$$F_{G} = \frac{6.67 \cdot 5.97 \cdot 6.42}{3.15^2}   10^{20} \cdot \frac{Nm^2}{((10^3)m)^2}$$

$$F_{G} = \frac{6.67 \cdot 5.97 \cdot 6.42}{3.15^2}   10^{20} \cdot \frac{N}{10^6}$$

$$F_{G} = \frac{6.67 \cdot 5.97 \cdot 6.42}{3.15^2}   10^{14} \cdot N$$

y aproximadamente:

$$F_{G} \approx 25.76 \cdot 10^{14} N$$

b) si la distancia entre la tierra y marte cambiara disminuyera a la mitad, calcule la nueva fuerza gravitacional entre ambos planetas.

partiendo desde la definición:

$$F_{G} = G \frac{m_1 \cdot m_2}{r^2}$$

y reemplazando con el nuevo valor de la distancia:

$$F_{G} = 6.67 \cdot 10^{-11} \left[\frac{Nm^2}{kg^2}\right] \frac{5.97 \cdot 10^{24} kg \cdot 6.42 \cdot 10^{23} kg}{(\frac{3.15 \cdot 10^{8} \ km}{2})^2}$$

simplificando:

$$F_{G} = 6.67 \cdot 10^{-11} (Nm^2) \frac{5.97 \cdot 10^{47} \cdot 6.42}{(\frac{3.15 \cdot 10^{8} \ km}{2})^2}$$

agrupando números, potencias de 10, y unidades:

$$F_{G} = \frac{4 \cdot 6.67 \cdot 5.97 \cdot 6.42}{3.15^2}  \frac{10^{36} }{10^{22}} \cdot N$$

seguimos simplificando:

$$F_{G} = \frac{4 \cdot 6.67 \cdot 5.97 \cdot 6.42}{3.15^2}  10^{14} \cdot N$$

y aproximadamente:

$$F_{G} \approx 103.05 \cdot 10^{14} N$$

con lo que concluimos que con una distancia disminuida en un factor de 2x, la fuerza gravitacional aumenta en 4x.

## ejercicio-04 (3 puntos)

un cuerpo posee una velocidad de $3[km/h]$. por 7 segundos recibe dos fuerzas contrarias $F_1 = 15[N]$ y $F_2=-4[N]$. si durante ese tiempo el cuerpo experimenta una aceleración de $5[m/s^2]$:

a) cuál es la masa del cuerpo?

solución:

por definición:

$\Sigma F = masa \cdot a$

reemplazando por las fuerzas y la aceleración:

$F_1 + F_2 = masa \cdot 5 \frac{m}{s^2}$

reemplazando los valores de fuerza:

$15N - 4N = masa \cdot 5 \frac{m}{s^2}$

$11 N = masa \cdot 5 \frac{m}{s^2}$

despejando la masa:

$masa = \frac{11 N}{5 \frac{m}{s^2}}$

y simplificando:

$masa = \frac{11 \frac{kg m}{s^2}}{5 \frac{m}{s^2}}$

$masa = \frac{11}{5} kg = 2.2 kg$

b) cuál es la velocidad final que alcanza el cuerpo a en t = 7 segundos?

solución:

usamos la ecuación de velocidad:

$v(t) = v_0 + a \cdot t$

reemplazando:

$v(t=7s) = 3 \frac{km}{h} + 5 \frac{m}{s^2} \cdot 7 s$

y simplificando:

$v(t=7s) = 3 \frac{1000m}{3600s} + 35 \frac{m}{s}$

$v(t=7s) = \frac{30m}{36s} + 35 \frac{m}{s}$

$v(t=7s) = \frac{5m}{6s} + 35 \frac{m}{s}$

$v(t=7s) \approx 35.83 \frac{m}{s}$
