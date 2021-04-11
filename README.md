# Atividade04
Exercício 01


package Exercicio04;

public class Aluno {
    
    private String Ra;
    private String Nome;
    private String Curso;
    
      public Aluno(){   
   
   }
    public Aluno (String Ra, String Nome, String Curso){
        this.Curso = Curso;
        this.Nome = Nome;
        this.Ra = Ra;
    }
 
    public String toString(){
     
        return "Curso: " + getCurso() + "\n"
             + "Nome: " + getNome() + "\n"
             + "Ra: " + getRa();
    
    }

    /**
     * @return the Ra
     */
    public String getRa() {
        return Ra;
    }

    /**
     * @param Ra the Ra to set
     */
    public void setRa(String Ra) {
        this.Ra = Ra;
    }

    /**
     * @return the Nome
     */
    public String getNome() {
        return Nome;
    }

    /**
     * @param Nome the Nome to set
     */
    public void setNome(String Nome) {
        this.Nome = Nome;
    }

    /**
     * @return the Curso
     */
    public String getCurso() {
        return Curso;
    }

    /**
     * @param Curso the Curso to set
     */
    public void setCurso(String Curso) {
        this.Curso = Curso;
    }
    
}
