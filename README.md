# Enseignant
Enseignant of homework

package dz.univeloued.tps.classes;

public class Enseignant extends Employe {
    private String specialite;

    public Enseignant(int id, String nom, String prenom, double salaire, String specialite) {
        super(id, nom, prenom, salaire);
        this.specialite = specialite;
    }

    @Override
    public String toString() {
        return super.toString() + " ma spécialité est: " + specialite;
    }
}
