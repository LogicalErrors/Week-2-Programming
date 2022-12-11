# Week-2-Programming
Week 2 Programming Code
//Ryan Bain
//ITD-1253-60498
//9-20-2022
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Week2_60438Project
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            label2.Text = "";   //This Removes the Text from the second label
        }

        private void Button2_Click(object sender, EventArgs e)

        {
            label2.Text = textBox1.Text;  //This copies the text that is inputed into the first textbox

        }

        private void Button3_Click(object sender, EventArgs e)

        {
            textBox1.Text = ""; //This removes the text that is inputed into the textbox

        }


        private void Button4_Click(object sender, EventArgs e)
        {
            this.Close(); //This closes the applacation 
        }
        private void label2_Click(object sender, EventArgs e)
        {
            label2.Text = textBox1.Text;
        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {
            
        }

        private void button3_Click_1(object sender, EventArgs e)
        {
            textBox1.Text = "";
        }

        private void button2_Click_1(object sender, EventArgs e)
        {
            label2.Text = textBox1.Text;
        }

        private void button4_Click_1(object sender, EventArgs e)
        {
            this.Close();
        }
    }
}
