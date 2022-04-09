/**
 * Use the VARIABLE.defl=VALUE notation to specify
 * default argument values.
 */
function sleep(seconds) {
  const date = Date.now();
  let currentDate = null;
  do {
    currentDate = Date.now();
  } while (currentDate - date < seconds * 1000);
}
//% color="#AA278D"
namespace test {
    //% block
    //% x.defl=42
    export function wait(x: number) {
        sleep(x);
    }
}
