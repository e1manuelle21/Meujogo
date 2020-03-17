import javax.swing.JFrame;

import meujogo.modulo.Fase;

public class Meujogo extends JFrame {
	
    
    public Meujogo(){
    add(new Fase());
	setTitle("Meu Jogo");
	setSize(1024,728);
	setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
	setLocationRelativeTo(null);
	this.setResizable(false);
	setVisible(true);	
}
    public static void main (String[]args) {
    new Meujogo();	
    	
    	
    }



}

