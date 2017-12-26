# credit.counter
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Credit_Counter
{
    public partial class Form_CreditCounter : Form
    {
        public Form_CreditCounter()
        {
            InitializeComponent();
        }

        private void pictureBox1_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit"); 
                //when the coin is clicked there must be a value for cost per credit
        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void label_0_Click(object sender, EventArgs e)
        {

        }

        private void pictureBox_2p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
                                
        }

        private void pictureBox_10p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }

        private void pictureBox_20p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }

        private void textBox_costpc_TextChanged(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
            MessageBox.Show("Set The Cost Per Credit");
            //when the coin is clicked there must be a value for cost per credit

        }

        private void pictureBox_1p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }

        private void btn_reset_Click(object sender, EventArgs e)
        {
            
        }

        private void groupBox_coins_Enter(object sender, EventArgs e)
        {

        }

        private void pictureBox_5p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }

        private void pictureBox_50p_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }

        private void pictureBox_1pound_Click(object sender, EventArgs e)
        {
            if (string.IsNullOrWhiteSpace(textBox_costpc.Text.Trim('0')))
                MessageBox.Show("Set The Cost Per Credit");
                //when the coin is clicked there must be a value for cost per credit
        }
    }
}
