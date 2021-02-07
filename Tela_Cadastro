import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JLabel;
import java.awt.Font;
import javax.swing.SwingConstants;
import javax.swing.JButton;
import java.awt.Color;

public class Tela_Cadastro {

	 JFrame frame;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Tela_Cadastro window = new Tela_Cadastro();
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
	public Tela_Cadastro() {
		initialize();
	}

	/**
	 * Initialize the contents of the frame.
	 */
	private void initialize() {
		frame = new JFrame();
		frame.getContentPane().setBackground(Color.WHITE);
		frame.setBounds(100, 100, 450, 300);
		frame.setDefaultCloseOperation(JFrame.DISPOSE_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		JLabel lblOpcao_Cadastro = new JLabel("Escolha a Op\u00E7\u00E3o de cadastro");
		lblOpcao_Cadastro.setHorizontalAlignment(SwingConstants.CENTER);
		lblOpcao_Cadastro.setFont(new Font("Tahoma", Font.PLAIN, 22));
		lblOpcao_Cadastro.setBounds(37, 21, 364, 43);
		frame.getContentPane().add(lblOpcao_Cadastro);
		
		JButton btnCadastro_Banco = new JButton("Cadastrar Banco");
		btnCadastro_Banco.setFont(new Font("Tahoma", Font.PLAIN, 15));
		btnCadastro_Banco.setBounds(96, 96, 239, 43);
		frame.getContentPane().add(btnCadastro_Banco);
		
		JButton btnCadastro_Agencia = new JButton("Cadastrar Ag\u00EAncia");
		btnCadastro_Agencia.setFont(new Font("Tahoma", Font.PLAIN, 15));
		btnCadastro_Agencia.setBounds(96, 150, 239, 43);
		frame.getContentPane().add(btnCadastro_Agencia);
		
		JButton btnCadastro_Conta = new JButton("Cadastrar Conta");
		btnCadastro_Conta.setFont(new Font("Tahoma", Font.PLAIN, 15));
		btnCadastro_Conta.setBounds(96, 204, 239, 43);
		frame.getContentPane().add(btnCadastro_Conta);
	}

}
