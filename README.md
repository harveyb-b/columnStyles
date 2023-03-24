# columnStyles
styles for the columns

foreach (DataGridViewColumn column in dataGridView1.Columns)

            {
            
                column.Width = 57;
                
                foreach (DataGridViewRow row in dataGridView1.Rows)
                
                {
                
                    row.Cells[column.Index].Style.Alignment = DataGridViewContentAlignment.MiddleCenter;
                    
                    row.Cells[column.Index].Style.Padding = new Padding(0);
                    
                    row.Cells[column.Index].Style.Font = new Font("Microsoft Sans Serif", 10);
                    
                }
                
            }
