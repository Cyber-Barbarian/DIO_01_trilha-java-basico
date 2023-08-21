# Herança

**As classes filha podem herdar atributos e métodos da classe pai**

A herança é um mecanismo da Orientação a Objeto que permite criar novas classes a partir de classes já existentes, aproveitando-se das características existentes na classe a ser estendida.

Imagine que precisássemos criar dois aplicativos de mensagem, clones do msn  e do telegram. Copiaríamos duas classes iguais? Não. Criaríamos um serviço pai com os métodos e atributos comuns e ele seria herdado pelas demais classes!

![heranca](<../.gitbook/assets/heranca.png>)

* Classe pai:
```java
//a classe ServicoMensagemInstantanea é ou representa
public class ServicoMensagemInstantanea {
	public void enviarMensagem() {
		//primeiro confirmar se esta conectado a internet
		validarConectadoInternet();
		System.out.println("Enviando mensagem");
		//depois de enviada, salva o histórico da mensagem
		salvarHistoricoMensagem();
	}
	public void receberMensagem() {
		System.out.println("Recebendo mensagem");
	}
	
	//métodos privadas, visíveis somente na classe
	private void validarConectadoInternet() {
		System.out.println("Validando se está conectado a internet");
	}
	private void salvarHistoricoMensagem() {
		System.out.println("Salvando o histórico da mensagem");
	}
}
```

* Classes filha:
```java
public class MSNMessenger extends ServicoMensagemInstantanea{

}

public class FacebookMessenger extends ServicoMensagemInstantanea {

}

public class Telegram extends ServicoMensagemInstantanea {

}
```

* Aplicação:
```java
public class ComputadorPedrinho {
	public static void main(String[] args) {
		
		MSNMessenger msn = new MSNMessenger();
		msn.enviarMensagem();
		msn.receberMensagem();
		
		FacebookMessenger fbm = new FacebookMessenger();
		fbm.enviarMensagem();
		fbm.receberMensagem();
		
		Telegram tlg = new Telegram();
		tlg.enviarMensagem();
		tlg.receberMensagem();
		
	}
}
```