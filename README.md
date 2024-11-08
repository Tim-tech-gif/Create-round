# Create-round
fn gen_shipments(mut shipments: Vec&lt;u32>) -> u32 {     let n = shipments.len();     let sum: u32 = shipments.iter().sum();     let avg = (sum as f32 / n as f32).round() as u32;     let mut moves = 0;
