import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JLabel;
import java.awt.Font;
import javax.swing.SwingConstants;
import javax.swing.JButton;
import javax.swing.UIManager;
import java.awt.Color;

public class Tela_Opcoes {

	JFrame frame;

	/**
	 * Launch the application.
	 */
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					Tela_Opcoes window = new Tela_Opcoes();
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
	public Tela_Opcoes() {
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
		
		JLabel lblOpcao = new JLabel("Escolha a Op\u00E7\u00E3o Desejada");
		lblOpcao.setHorizontalAlignment(SwingConstants.CENTER);
		lblOpcao.setFont(new Font("Tahoma", Font.PLAIN, 22));
		lblOpcao.setBounds(28, 27, 376, 33);
		frame.getContentPane().add(lblOpcao);
		
		JButton btnExibir_Extrato = new JButton("Exibir Extrato");
		btnExibir_Extrato.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnExibir_Extrato.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnExibir_Extrato.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnExibir_Extrato.setBounds(75, 89, 149, 41);
		frame.getContentPane().add(btnExibir_Extrato);
		
		JButton btnRealizar_transferencia = new JButton("Realizar Transfer\u00EAncia");
		btnRealizar_transferencia.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnRealizar_transferencia.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnRealizar_transferencia.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnRealizar_transferencia.setBounds(75, 141, 149, 41);
		frame.getContentPane().add(btnRealizar_transferencia);
		
		JButton btnExibir_Saldo = new JButton("Exibir Saldo");
		btnExibir_Saldo.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnExibir_Saldo.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnExibir_Saldo.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnExibir_Saldo.setBounds(75, 193, 149, 41);
		frame.getContentPane().add(btnExibir_Saldo);
		
		JButton btnGerar_Chave_Pix = new JButton("Gerar Chave Pix");
		btnGerar_Chave_Pix.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnGerar_Chave_Pix.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnGerar_Chave_Pix.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnGerar_Chave_Pix.setBounds(234, 89, 149, 41);
		frame.getContentPane().add(btnGerar_Chave_Pix);
		
		JButton btnSaque = new JButton("Saque");
		btnSaque.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnSaque.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnSaque.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnSaque.setBounds(234, 141, 149, 41);
		frame.getContentPane().add(btnSaque);
		
		JButton btnDeposito = new JButton("Deposito");
		btnDeposito.setForeground(UIManager.getColor("inactiveCaptionText"));
		btnDeposito.setFont(new Font("Tahoma", Font.PLAIN, 12));
		btnDeposito.setBackground(UIManager.getColor("inactiveCaptionText"));
		btnDeposito.setBounds(234, 193, 149, 41);
		frame.getContentPane().add(btnDeposito);
	}

}
