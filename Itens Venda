public class itensVenda extends Produto {

    private Integer id;
    private String produto;
    private Integer qntd;
    private Double desconto;

    public Integer getId() {
        return id;
    }

    public void setId(Integer id) {
        this.id = id;
    }

    public String getProduto() {
        return produto;
    }

    public void setProduto(String produto) {
        this.produto = produto;
    }

    public Integer getQntd() {
        return qntd;
    }

    public void setQntd(Integer qntd) {
        this.qntd = qntd;
    }

    public Double getDesconto() {
        return desconto;
    }

    public void setDesconto(Double desconto) {
        this.desconto = desconto;
    }

    public Double valorFinal(Double valor, Double IPI, Double desconto){
        return this.getValor() + getIPI() - getDesconto();
    }
}
