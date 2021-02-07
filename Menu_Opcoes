import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JButton;
import javax.swing.JLabel;
import java.awt.Font;
import javax.swing.SwingConstants;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;
import java.awt.Color;

public class Menu_Opcoes {

	 JFrame frame;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Menu_Opcoes window = new Menu_Opcoes();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	/**
	 * Create the application.
	 */
	public Menu_Opcoes() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.getContentPane().setBackground(Color.WHITE);
		frame.setBounds(100, 100, 253, 300);
		frame.setDefaultCloseOperation(JFrame.DISPOSE_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		JButton btnRealizar_Cadastro = new JButton("Realizar Cadastro");
		btnRealizar_Cadastro.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				Tela_Cadastro window = new Tela_Cadastro();
				window.frame.setVisible(true);
				
			}
		});
		btnRealizar_Cadastro.setFont(new Font("Tahoma", Font.PLAIN, 14));
		btnRealizar_Cadastro.setBounds(32, 75, 176, 33);
		frame.getContentPane().add(btnRealizar_Cadastro);
		
		JButton btnManutencao_Geral = new JButton("Manuten\u00E7\u00E3o Geral");
		btnManutencao_Geral.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				Tela_Manutencao window = new Tela_Manutencao();
				window.frame.setVisible(true);
				
			}
		});
		btnManutencao_Geral.setFont(new Font("Tahoma", Font.PLAIN, 14));
		btnManutencao_Geral.setBounds(32, 119, 176, 33);
		frame.getContentPane().add(btnManutencao_Geral);
		
		JButton btnOpcoes = new JButton("Op\u00E7\u00F5es");
		btnOpcoes.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				
				Tela_Opcoes window = new Tela_Opcoes();
				window.frame.setVisible(true);
				
			}
		});
		btnOpcoes.setFont(new Font("Tahoma", Font.PLAIN, 14));
		btnOpcoes.setBounds(32, 163, 176, 33);
		frame.getContentPane().add(btnOpcoes);
		
		JLabel lblEscolha_Opcao = new JLabel("Escolha a op\u00E7\u00E3o desejada");
		lblEscolha_Opcao.setHorizontalAlignment(SwingConstants.CENTER);
		lblEscolha_Opcao.setFont(new Font("Tahoma", Font.PLAIN, 14));
		lblEscolha_Opcao.setBounds(32, 11, 176, 33);
		frame.getContentPane().add(lblEscolha_Opcao);
	}

}
