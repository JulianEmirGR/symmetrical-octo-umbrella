import java.util.ArrayList;
import java.util.List;

public class WhatsAppChat {
    private List<Message> messages;
    
    public WhatsAppChat() {
        this.messages = new ArrayList<>();
        initializeChat();
    }
    
    private void initializeChat() {
        // 6 de Febrero, 2025
        messages.add(new Message("06/02/25", "3:56 p. m.", "Sistema", 
            "Los mensajes y las llamadas están cifrados de extremo a extremo. Nadie fuera de este chat, ni siquiera WhatsApp, puede leerlos ni escucharlos. Toca para obtener más información."));
        
        // 7 de Febrero, 2025
        messages.add(new Message("07/02/25", "11:46 p. m.", "Magaly✨", "Hola"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Magaly✨", "Soy Moni"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Magaly✨", "Podemos hablar"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Fabián", "Hola Moni Moni"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Fabián", "Ya me andaba durmiendo 😴"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Fabián", "Pero si claro que sí"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Magaly✨", "Crees que te pueda hablar"));
        messages.add(new Message("07/02/25", "11:46 p. m.", "Magaly✨", "O haci por mensaje"));
        messages.add(new Message("07/02/25", "11:47 p. m.", "Fabián", "Por mensaje xfa por qué ya estoy acostado y mi mamá se está durmiendo mi Moni"));
        messages.add(new Message("07/02/25", "11:47 p. m.", "Fabián", "Te leo bonita."));
        messages.add(new Message("07/02/25", "11:48 p. m.", "Fabián", "Moni"));
        messages.add(new Message("07/02/25", "11:51 p. m.", "Magaly✨", "Gracias"));
        messages.add(new Message("07/02/25", "11:51 p. m.", "Magaly✨", "Más que nd quiero una p"));
        messages.add(new Message("07/02/25", "11:51 p. m.", "Magaly✨", "Opinión"));
        messages.add(new Message("07/02/25", "11:51 p. m.", "Fabián", "Siiiii"));
        messages.add(new Message("07/02/25", "11:51 p. m.", "Magaly✨", "Tu crees que valgo la pena"));
        messages.add(new Message("07/02/25", "11:52 p. m.", "Fabián", "Claro que vales la pena, mil veces si Moni."));
        messages.add(new Message("07/02/25", "11:52 p. m.", "Fabián", "Que paso"));
        messages.add(new Message("07/02/25", "11:52 p. m.", "Magaly✨", "Tu crees que merezco ser querida"));
        messages.add(new Message("07/02/25", "11:52 p. m.", "Fabián", "Mereces eso y más."));
        messages.add(new Message("07/02/25", "11:53 p. m.", "Fabián", "Tu eres muy fuerte Mi Moni"));
        messages.add(new Message("07/02/25", "11:53 p. m.", "Fabián", "Que paso"));
        messages.add(new Message("07/02/25", "11:53 p. m.", "Magaly✨", "Más bien que no"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Fabián", "Hijole no me siento bien al leerte decir eso"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Fabián", "Quieres que te visite mañana?"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Fabián", "🥺"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Magaly✨", "Antes de eso debo contarte algo"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Fabián", "Siii"));
        messages.add(new Message("07/02/25", "11:54 p. m.", "Magaly✨", "No eh estado bien"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "Que pasa"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Magaly✨", "Fabi estoy embarazada"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "Enserio"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Magaly✨", "Y es de alto riesgo"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "Y como te sientes"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "Enserio ya te checaste"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Magaly✨", "Aunque me apene decírtelo"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "Que te dicen"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Magaly✨", "Si"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Fabián", "No por que, no te preocupes"));
        messages.add(new Message("07/02/25", "11:55 p. m.", "Magaly✨", "Pues eh estado en chequeos y todo"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Magaly✨", "Y es de alto riesgo"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Magaly✨", "Por qué tengo anemia"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Fabián", "Me imagino pero no pierdas la fé"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Fabián", "Vas a ver qué estaran bien"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Magaly✨", "Y además me quiere dar diabetes"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Magaly✨", "No la pierdo"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Fabián", "Eso se contra resta Moni"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Fabián", "No pienses siquiera eso"));
        messages.add(new Message("07/02/25", "11:56 p. m.", "Magaly✨", "Eso no es lo que me preocupa"));
        messages.add(new Message("07/02/25", "11:57 p. m.", "Fabián", "Procura comer bien y vas a estar bien"));
        messages.add(new Message("07/02/25", "11:57 p. m.", "Magaly✨", "Lo que si es que justo lo que no quería vivir lo estoy pasando"));
        messages.add(new Message("07/02/25", "11:57 p. m.", "Fabián", "Que paso"));
        messages.add(new Message("07/02/25", "11:57 p. m.", "Magaly✨", "Pues siento que a mí pareja no le interesó"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Fabián", "Por qué piensas eso"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Magaly✨", "Por más que le dije deja de fumar cerca de mi o no lo hagas me da asco"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Fabián", "Debes interesarle"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Magaly✨", "Lo hizo"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Fabián", "Ah ya, no pues de ahí viene todo."));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Magaly✨", "Y por el mi embarazo de alto riesgo"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Fabián", "Que mal plan"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Magaly✨", "Si"));
        messages.add(new Message("07/02/25", "11:58 p. m.", "Fabián", "Si necesitas controlar eso"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Magaly✨", "Lo peor es que lo único que quiero es su compañía y saber que no estoy sola"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Fabián", "No te puedes exponer así"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Magaly✨", "Y en vez de estar conmigo"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Magaly✨", "Mejor se va con sus amigos"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Fabián", "Es lo malo de los morrillos que no saben lo que quieren"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Fabián", "Perdón que te lo diga así"));
        messages.add(new Message("07/02/25", "11:59 p. m.", "Magaly✨", "Y hoy recibí una noticia y le dije porfa solo abrázame y acompáñame"));
        
        // 8 de Febrero, 2025
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Habla con el"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Y que paso"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Magaly✨", "Ya lo eh intentado"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Magaly✨", "Se fue con un amigo de el a tomar y fumar"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Mmmm no"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Magaly✨", "Y mejor me consoló mi mamá"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Así no se va a poder"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Magaly✨", "Lo seee"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Bueno yo te deseo todo el bien verdad"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Pero si necesitas ponerle un alto"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Magaly✨", "Pero tampoco quiero quedarme sola"));
        messages.add(new Message("08/02/25", "12:00 a. m.", "Fabián", "Ahorita"));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Fabián", "Por qué luego será más difícil"));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Fabián", "Me imagino"));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Magaly✨", "Y lo peor es que me arrepiento de todo esto"));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Magaly✨", "Y quisiera morirme"));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Fabián", "No te preocupes todo pasa por algo."));
        messages.add(new Message("08/02/25", "12:01 a. m.", "Fabián", "Y vas a estar bien mi Moni te lo prometo"));
        messages.add(new Message("08/02/25", "12:02 a. m.", "Magaly✨", "Es como dice mi familia \"quien te va a querer con hijos\""));
        messages.add(new Message("08/02/25", "12:02 a. m.", "Fabián", "No falta quien tu no pierdas la fé, tu eres muy bonita y buena onda"));
        messages.add(new Message("08/02/25", "12:02 a. m.", "Magaly✨", "Te juro que lo único que quiero es morirme"));
        messages.add(new Message("08/02/25", "12:02 a. m.", "Fabián", "No no me digas eso"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Magaly✨", "Es que soy una tonta"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Fabián", "Debes echarle ganas"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Magaly✨", "Cómo deje que esto pasará"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Fabián", "Nadie es tonto, solo que son cosas que pasan mi Moni"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Magaly✨", "Ay pero yo soy más inteligente como para pasar esto"));
        messages.add(new Message("08/02/25", "12:03 a. m.", "Magaly✨", "No lo merezco"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Fabián", "Si tú mereces ser feliz mamita"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Fabián", "🙏🏽"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Magaly✨", "Lo único que quiero es que alguien me diga que no estoy sola y que por fin me quieran tal y como soy"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Fabián", "🙏🏽"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Magaly✨", "Lo sé pero la vida no lo quieres"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Magaly✨", "Quiere *"));
        messages.add(new Message("08/02/25", "12:04 a. m.", "Fabián", "Vas a Estar bien"));
        messages.add(new Message("08/02/25", "12:05 a. m.", "Fabián", "Te lo prometo"));
        messages.add(new Message("08/02/25", "12:05 a. m.", "Fabián", "Tuy. Tu bebé"));
        messages.add(new Message("08/02/25", "12:08 a. m.", "Magaly✨", "Lo sé"));
        messages.add(new Message("08/02/25", "12:08 a. m.", "Magaly✨", "Pero no quiero estar bien"));
        messages.add(new Message("08/02/25", "12:08 a. m.", "Magaly✨", "Lo único que quiero es ya no estar aquiii"));
        messages.add(new Message("08/02/25", "12:08 a. m.", "Magaly✨", "De que me sirve"));
        messages.add(new Message("08/02/25", "12:09 a. m.", "Fabián", "No mi Moni, échale ganas mamita"));
        messages.add(new Message("08/02/25", "12:09 a. m.", "Fabián", "Yo te quiero mucho"));
        messages.add(new Message("08/02/25", "12:09 a. m.", "Fabián", "Y te juro que estarás bien"));
        messages.add(new Message("08/02/25", "12:22 a. m.", "Magaly✨", "No creo"));
        messages.add(new Message("08/02/25", "6:59 a. m.", "Fabián", "Si mi Moniiiii"));
        messages.add(new Message("08/02/25", "6:59 a. m.", "Fabián", "Cómo tas"));
        messages.add(new Message("08/02/25", "10:36 a. m.", "Magaly✨", "Hola"));
        messages.add(new Message("08/02/25", "10:36 a. m.", "Magaly✨", "Pues dos que tres"));
        messages.add(new Message("08/02/25", "10:36 a. m.", "Magaly✨", "Me vienes a ver"));
        messages.add(new Message("08/02/25", "10:43 a. m.", "Fabián", "Si no se bien a qué hora salgo"));
        messages.add(new Message("08/02/25", "10:43 a. m.", "Fabián", "Pero te mando msj va"));
        messages.add(new Message("08/02/25", "11:01 a. m.", "Magaly✨", "Va"));
        messages.add(new Message("08/02/25", "7:52 p. m.", "Magaly✨", "Cómo va el partido"));
        messages.add(new Message("08/02/25", "8:26 p. m.", "Fabián", "<Multimedia omitido>"));
        messages.add(new Message("08/02/25", "8:33 p. m.", "Magaly✨", "Ay"));
        messages.add(new Message("08/02/25", "8:33 p. m.", "Magaly✨", "Y contra quién juegan"));
        messages.add(new Message("08/02/25", "8:34 p. m.", "Magaly✨", "<Multimedia omitido>"));
        messages.add(new Message("08/02/25", "8:34 p. m.", "Magaly✨", "<Multimedia omitido>"));
        messages.add(new Message("08/02/25", "9:30 p. m.", "Fabián", "Contra Toluca"));
        messages.add(new Message("08/02/25", "9:30 p. m.", "Fabián", "Enserio"));
        messages.add(new Message("08/02/25", "9:30 p. m.", "Fabián", "Yo te lo invito."));
        messages.add(new Message("08/02/25", "9:41 p. m.", "Magaly✨", "Ay pues gracias 💗"));
        messages.add(new Message("08/02/25", "10:34 p. m.", "Fabián", "Se eliminó este mensaje."));
        messages.add(new Message("08/02/25", "10:41 p. m.", "Fabián", "Se eliminó este mensaje."));
        messages.add(new Message("08/02/25", "10:55 p. m.", "Magaly✨", "Qubpado"));
        messages.add(new Message("08/02/25", "10:55 p. m.", "Magaly✨", "Que paso"));
        messages.add(new Message("08/02/25", "10:55 p. m.", "Fabián", "Si puedes hablar"));
        messages.add(new Message("08/02/25", "10:56 p. m.", "Magaly✨", "Sii"));
        messages.add(new Message("08/02/25", "10:56 p. m.", "Fabián", "Es que borre los mensajes por qué te decía lo que ya sabes que estás bien bonita y que tenía ganas de verte"));
        messages.add(new Message("08/02/25", "10:56 p. m.", "Fabián", "Pero pensé que podría meterte en problemas"));
        messages.add(new Message("08/02/25", "10:56 p. m.", "Fabián", "Mejor los borre"));
        messages.add(new Message("08/02/25", "10:57 p. m.", "Magaly✨", "Gracias y yo también"));
        messages.add(new Message("08/02/25", "10:57 p. m.", "Fabián", "Ya te hacía dormidita"));
        messages.add(new Message("08/02/25", "10:57 p. m.", "Magaly✨", "No"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Magaly✨", "Lo que pasa es que me dormí en la tarde"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Magaly✨", "Y no puedo dormir ahora"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Fabián", "Ah okk"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Fabián", "Me imagino"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Magaly✨", "Y además estoy sola jaja"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Fabián", "Yo voy llegando del estadio 🏟️"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Fabián", "Ah ok"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Magaly✨", "Que bueno"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Magaly✨", "Y que tal ?"));
        messages.add(new Message("08/02/25", "10:58 p. m.", "Fabián", "Estuvo bien el juego"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Estuve en la porra de Toluca"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Y son bien manchados"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Jejejje"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Magaly✨", "Me alegro"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Magaly✨", "Jaja sii"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Pero sacamos como a 3 personas por aventar cerveza"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Magaly✨", "Ouu yap"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Y tu mamá como está"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Fabián", "Tus hermanas"));
        messages.add(new Message("08/02/25", "10:59 p. m.", "Magaly✨", "Pues mi mamá hace poco que enfermo"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "Creo que el otro día mire ala Ary"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "O como se llama 😅"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Magaly✨", "Tenía anemia"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "Ah ok pero ya está bien?"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Magaly✨", "Si jaja"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Magaly✨", "Si ya esta bien"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "Creo si era ella"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Magaly✨", "Bien todos bien"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "Ok"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "Por qué me miró así como que también me conocía 😅"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Fabián", "O quién sabe"));
        messages.add(new Message("08/02/25", "11:00 p. m.", "Magaly✨", "Jaja si creo que me comentó slvo"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Magaly✨", "Algo"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Fabián", "Traía una sudadera gris como que venía de la escuela creo por la Cuenca Florida en Echeveste"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Fabián", "Ah ok"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Fabián", "Solo que yo llevaba prisa es cuando iba a trabajar ala palenque de la feria."));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Magaly✨", "Ya me aburrii"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Magaly✨", "Ay yap"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Fabián", "Que paso"));
        messages.add(new Message("08/02/25", "11:01 p. m.", "Magaly✨", "Yo fui cono el domingo que paso"));
        messages.add(new Message("08/02/25", "11:02 p. m.", "Fabián", "Ah ok"));
        messages.add(new Message("08/02/25", "11:02 p. m.", "Magaly✨", "No puedo dormir"));
        messages.add(new Message("08/02/25", "11:02 p. m.", "Magaly✨", "Y tampoco se que hacer"));
        messages.add(new Message("08/02/25", "11:05 p. m.", "Fabián", "Una película mami"));
        messages.add(new Message("08/02/25", "11:05 p. m.", "Fabián", "Yo me voy a bañar a cenar y a dormir que mañana entro muy temprano"));
        messages.add(new Message("08/02/25", "11:05 p. m.", "Fabián", "05:15"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "Si está bien"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "No pues si algo"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Fabián", "Si mamacita"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "Proveho"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Fabián", "Trata de descansar si"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "Si :)"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Fabián", "Y te debo tu regalo y tú elote va"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "Va"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Fabián", "Cuídate te quiero 🤍"));
        messages.add(new Message("08/02/25", "11:06 p. m.", "Magaly✨", "Gracias e igualmente"));
        messages.add(new Message("08/02/25", "11:07 p. m.", "Fabián", "Igualmente que"));
        messages.add(new Message("08/02/25", "11:22 p. m.", "Magaly✨", "Te quiero"));
        messages.add(new Message("08/02/25", "11:22 p. m.", "Magaly✨", "Y cuídate mucho"));
        messages.add(new Message("08/02/25", "11:23 p. m.", "Fabián", "Siiii"));
        messages.add(new Message("08/02/25", "11:24 p. m.", "Magaly✨", "Me alegra volver hablarte"));
        messages.add(new Message("08/02/25", "11:25 p. m.", "Fabián", "Si Mi Moni a mi también 🙏🏽🤍"));
        
        // 9 de Febrero, 2025
        messages.add(new Message("09/02/25", "12:51 p. m.", "Magaly✨", "Hola"));
        messages.add(new Message("09/02/25", "12:53 p. m.", "Fabián", "<Multimedia omitido>"));
        messages.add(new Message("09/02/25", "1:20 p. m.", "Magaly✨", "Ya mejor y tú"));
        messages.add(new Message("09/02/25", "3:35 p. m.", "Fabián", "<Multimedia omitido>"));
        messages.add(new Message("09/02/25", "4:15 p. m.", "Magaly✨", "Garcías <Se editó este mensaje.>"));
        messages.add(new Message("09/02/25", "4:15 p. m.", "Magaly✨", "Ya comiste"));
        messages.add(new Message("09/02/25", "4:19 p. m.", "Fabián", "<Multimedia omitido>"));
        messages.add(new Message("09/02/25", "5:03 p. m.", "Magaly✨", "Que ben"));
        messages.add(new Message("09/02/25", "5:03 p. m.", "Magaly✨", "Bueno"));
        messages.add(new Message("09/02/25", "5:03 p. m.", "Magaly✨", "Yo no eh podido"));
        messages.add(new Message("09/02/25", "5:03 p. m.", "Magaly✨", "Todo me da asco"));
        messages.add(new Message("09/02/25", "6:20 p. m.", "Fabián", "Me imagino"));
        messages.add(new Message("09/02/25", "6:21 p. m.", "Fabián", "Debes comer  bien"));
        messages.add(new Message("09/02/25", "6:21 p. m.", "Fabián", "Moni"));
        messages.add(new Message("09/02/25", "8:16 p. m.", "Magaly✨", "Ay que rico se ve"));
        messages.add(new Message("09/02/25", "8:28 p. m.", "Fabián", "Si mi Moniiiii"));
        messages.add(new Message("09/02/25", "8:28 p. m.", "Fabián", "Esta rico"));
        messages.add(new Message("09/02/25", "8:39 p. m.", "Magaly✨", "Ay ya me antojaste"));
        messages.add(new Message("09/02/25", "9:26 p. m.", "Fabián", "Me imagino 🥺"));
        messages.add(new Message("09/02/25", "10:12 p. m.", "Magaly✨", "Ay Deli 💗🥹"));
        messages.add(new Message("09/02/25", "10:25 p. m.", "Fabián", "Siii la vdd hoy me pase"));
        messages.add(new Message("09/02/25", "10:25 p. m.", "Fabián", "Comí n chingo"));
        messages.add(new Message("09/02/25", "10:48 p. m.", "Magaly✨", "Esta bien"));
        messages.add(new Message("09/02/25", "10:48 p. m.", "Magaly✨", "Jaja"));
        messages.add(new Message("09/02/25", "10:48 p. m.", "Magaly✨", "Yo ya pude comer algo"));
        messages.add(new Message("09/02/25", "10:48 p. m.", "Magaly✨", "Mi mamá me hizo una ensalada"));
        
        // 10 de Febrero, 2025
        messages.add(new Message("10/02/25", "5:17 a. m.", "Fabián", "Ah ok que bueno mi Moni"));
        messages.add(new Message("10/02/25", "5:17 a. m.", "Fabián", "Ah qué rico."));
        messages.add(new Message("10/02/25", "12:18 p. m.", "Magaly✨", "Hola y si jaja"));
        messages.add(new Message("10/02/25", "12:19 p. m.", "Fabián", "Cómo seguiste mi Moni"));
        messages.add(new Message("10/02/25", "1:54 p. m.", "Fabián", "null"));
        messages.add(new Message("10/02/25", "2:18 p. m.", "Magaly✨", "Masó menos"));
        messages.add(new Message("10/02/25", "2:18 p. m.", "Magaly✨", "Que padre"));
        messages.add(new Message("10/02/25", "3:40 p. m.", "Magaly✨", "Voliv"));
        messages.add(new Message("10/02/25", "3:40 p. m.", "Magaly✨", "Fui a mi pimer ultrasonido"));
        messages.add(new Message("10/02/25", "3:43 p. m.", "Fabián", "Oh y que tal"));
        messages.add(new Message("10/02/25", "3:43 p. m.", "Fabián", "Que te dijeron"));
        messages.add(new Message("10/02/25", "3:54 p. m.", "Magaly✨", "null"));
        messages.add(new Message("10/02/25", "3:58 p. m.", "Magaly✨", "null"));
    }
    
    public List<Message> getMessages() {
        return messages;
    }
    
    public void printChat() {
        for (Message message : messages) {
            System.out.println(message);
        }
    }
    
    public static void main(String[] args) {
        WhatsAppChat chat = new WhatsAppChat();
        chat.printChat();
    }
}

class Message {
    private String date;
    private String time;
    private String author;
    private String content;
    
    public Message(String date, String time, String author, String content) {
        this.date = date;
        this.time = time;
        this.author = author;
        this.content = content;
    }
    
    // Getters
    public String getDate() { return date; }
    public String getTime() { return time; }
    public String getAuthor() { return author; }
    public String getContent() { return content; }
    
    @Override
    public String toString() {
        return date + " " + time + " - " + author + ": " + content;
    }
}