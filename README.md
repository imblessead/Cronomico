# Cronomico
Cronomico

package exemplos;

public class ProjetoCronometro {

	public static void main(String[] args) {
		try {
			for (int s = 0; s <60; s++) {
				for (int m = 0; m <60; m++) {
					//System.out.println(s);
					System.out.println(s+":"+m);
					//Timer para deixar mais lento na hora de compilar
					Thread.sleep(1000);
				}
			}
		} catch (Exception e) {
			
		}
		System.out.println("Nao foi possivel adicionar um segundo em cada execução do laço for");
	}

}

