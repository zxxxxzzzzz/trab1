package controller;

import java.util.Scanner;

public class JokenPo {

	public static void main(String[] args) {

		int jogador, computador;
		Scanner teclado = new Scanner(System.in);
		System.out.println("____Vamos jogar pedra papel tesoura____");
		System.out.println("");
		System.out.println("1. Pedra");
		System.out.println("2. Papel");
		System.out.println("3. Tesoura");
		System.out.println("4. lagarto");
		System.out.println("5. Spock");
		System.out.println("Digite a opção desejada");

		jogador = teclado.nextInt();
		System.out.println("");
		switch (jogador) {
		case 1:
			System.out.println("Jogador escolheu pedra");
			break;
		case 2:
			System.out.println("jogador escolheu papel");
			break;
		case 3:
			System.out.println("jogador escolheu tesoura");
			break;
		case 4:
			System.out.println("jogador escolheu lagarto");
			break;
		case 5:
			System.out.println("jogador escolheu spock");
			break;
		default:
			System.out.println("Opção invalida");
			break;
		}
		computador = (int) (Math.random() * 5 + 1);
		teclado.close();
		switch (computador) {
		case 1:
			System.out.println("computador escolheu pedra");
			break;
		case 2:
			System.out.println("computador escolheu papel");
			break;
		case 3:
			System.out.println("computador escolheu tesoura");
			break;
		case 4:
			System.out.println("computador escolheu lagarto");
			break;
		case 5:
			System.out.println("computador escolheu spock");
			break;
		}
		System.out.println("");
		if (jogador == computador) {
			System.out.println("EMPATE");
		} else {
			if ((jogador == 1 && computador == 3) || (jogador == 2 && computador == 1)
					|| (jogador == 3 && computador == 2) || (jogador == 4 && computador == 2)
					|| (jogador == 4 && computador == 5) || (jogador == 5 && computador == 1)
					|| (jogador == 5 && computador == 3)) {

				System.out.println("JOGADOR VENCEU");
			} else {
				System.out.println("COMPUTADOR VENCEU");
			}

		}
	}

}
