/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Main.java to edit this template
 */
package caso1estudio;

import javax.swing.JOptionPane;

/**
 *
 * @author rvale
 */
public class Caso1estudio {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    }

        String nombreCliente=JOptionPane.showInputDialog("Digite el nombre del cliente");
        String cedulaCliente=JOptionPane.showInputDialog("Digite el numero de cedula del cliente");
        String codigoFactura=JOptionPane.showInputDialog("Digite el codigo de factura");
        double monto = Double.parseDouble(JOptionPane.showInputDialog("Digite el total de su monto"));
        int productoElectrico = Integer.parseInt(JOptionPane.showInputDialog("Digitel monto de productos electricos adquiridos"));
        int productoAutomotriz = Integer.parseInt(JOptionPane.showInputDialog("Digite el monto de productos automotriz adquiridos"));
        int productoConstruccion = Integer.parseInt(JOptionPane.showInputDialog("Digite el monto de productos para construccion"));
        
        Factura factura = new Factura (nombreCliente, cedulaCliente,codigoFactura,monto,productoElectrico, productoAutomotriz, productoConstruccion);
        //calcular comision
        double comision = factura.calcularComision();
        //muestro resultados
        //System.out.println("La factura esta a nombre del cliente: "+nombreCliente);
        //System.out.println("La cedula del cliente es: "+cedulaCliente);
        //System.out.println("El codigo de la factura es: "+codigoFactura);
        //System.out.println("MONTO TOTAL: "+monto);
        //System.out.println("Cantidad de productos electricos: "+productoElectrico);
        //System.out.println("Cantidad de productos automotrices: "+productoAutomotriz);
        //System.out.println("Cantidad de productos de construccion: "+productoConstruccion);
        //System.out.println("COMISIONES: "+comision);
        
        JOptionPane.showMessageDialog(null, "La factura esta a nombre del cliente" + nombreCliente + " La cedula del cliente: " + cedulaCliente+
                "Codigo de factura" + codigoFactura + " MONTO TOTAL: " + monto + " CANTIDAD DE PRODUCTOS ELECTRICOS: " + productoElectrico + " CANTIDAD DE PRODUCTOS AUTOMOTRIZ: "
        + productoAutomotriz +"CANTIDAD DE PRODUCTOS DE CONSTRUCCION: " + productoConstruccion + " COMISIONES: " + comision + ".");
    
        
    }
    

        
           

